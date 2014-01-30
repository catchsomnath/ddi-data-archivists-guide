===============
5.5. Good practices for completing the External Resources description
===============

The External Resources are all materials related to the study others than the data files. They include documents (such as the questionnaires, interviewer’s manuals, reports, etc), programs (data entry, editing, tabulation, and analysis), maps, photos, and others. To document external resources, the IHSN Toolkit uses the Dublin Core metadata standard (which complements the DDI standard).

.. raw:: html

		<table border="1" cellpadding="0" cellspacing="0">
		<tbody>
        <tr>
            <td valign="top">
                <p>
                    Label
                </p>
            </td>
            <td valign="top">
                <p>
                    This is the label that will be used to display a hyper link to the attached document. It can be the title, name, or an abbreviated version
                    of the title.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Resource
                </p>
            </td>
            <td valign="top">
                <p>
                    The resource is used to point to the file that will be attached and distributed. The folder where the document is found is a relative path
                    and should be the folder that will be pasted into the **\document path. Once you have pointed to the specified resource make sure you check
                    file access by clicking the folder icon to the right of the entry field.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Type
                </p>
            </td>
            <td valign="top">
                <p>
                    This is crucial information. A controlled vocabulary is provided. The selection of the type is important as it determines the way it will
                    be presented or displayed to the user in the final output. The following are the choices:
                </p>
                <ul>
                    <li>Document Administrative: This includes materials such as the survey budget; grant agreement with sponsors; list of staff and interviewers, etc. </li>
					<li>Document Analytical: Documents that present analytical output (academic papers, etc. This does not include the descriptive survey report (see below). </li>
					<li>Document Questionnaire: the actual questionnaire(s) used in the field.</li>
					<li>Document Reference: Any reference documents that are not directly related to the specific dataset, but that provide background information regarding methodology, etc. For international standard surveys, this may for example include the generic guidelines provided by the survey sponsor.</li>
					<li>Document Report: Survey reports, studies and other reports that use the data as the basis for their findings.</li>
					<li>Document Technical: Methodological documents related to survey design, interviewer’s and supervisor’s manuals, editing specifications, data entry operator’s manual, tabulation and analysis plan, etc.</li>
					<li>Document Other: Miscellaneous items</li>
					<li>Audio: audio type files.</li>
					<li>Map: Any cartographic information.</li>
					<li>Photo: Photos can provide good documentary evidence of a survey.</li>
					<li>Program: programs generated during data entry and analysis (data entry, editing, tabulation and analysis). These can be zipped together (include a brief summary report to describe the contents)</li>
					<li>Table: Tabulations such as confidence intervals that may not be included in a general report.</li>
					<li>Video: video type files provided as additional visual information</li>
					<li>Website: Link to related website(s), such as a link to a Redatam server, or to the website of the survey sponsor in the case of	international survey programs like the DHS, LSMS, or MICS).</li>
					<li>Database: any databases related to the survey (e.g., a Devinfo database providing the aggregated results of the survey).</li>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Title
                </p>
            </td>
            <td valign="top">
                <p>
                    Full title of the document as it is provided on the cover page.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Subtitle
                </p>
            </td>
            <td valign="top">
                <p>
                    Subtitle if relevant.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Author(s)
                </p>
            </td>
            <td valign="top">
                <p>
                    Include all authors that are listed on the report.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Date
                </p>
            </td>
            <td valign="top">
                <p>
                    Date of the publication of the report or resource (at least month and year). For reports, this is most likely stated on the cover page of
                    the document. For other types of resources, put here the date the resource was produced.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Country
                </p>
            </td>
            <td valign="top">
                <p>
                    The country (or countries) that are covered by the associated document.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Language
                </p>
            </td>
            <td valign="top">
                <p>
                    Use the Language element to list all languages which appear in a resource. The languages should be selected from the drop-down list, and
                    each language should appear on its own line. The proposed controlled vocabulary is based on ISO 639-3s.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Format
                </p>
            </td>
            <td valign="top">
                <p>
                    The file format provides information on the kind of electronic document being provided. This includes: PDF, Word, Excel etc. This is a
                    controlled vocabulary. If the controlled vocabulary does not provide the format you need, type it (or add it in the controlled vocabulary
                    using the Toolkit Template Editor). Providing information on the format will inform the user on the software needed to open the file.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    ID Number
                </p>
            </td>
            <td valign="top">
                <p>
                    If there is a unique ID number which references the document (such as a Library of Congress number or a World Bank Publication number)
                    include this as the ID Number.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Contributor(s)
                </p>
            </td>
            <td valign="top">
                <p>
                    Include the names of all organizations that have been involved or contributed to producing the publication. This included funding sources
                    as well as authoring entities.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Publisher(s)
                </p>
            </td>
            <td valign="top">
                <p>
                    Include the official organization(s) accredited with disseminating the report.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Rights
                </p>
            </td>
            <td valign="top">
                <p>
                    Some resources are protected by copyrights. Use the Rights element to provide a clear and complete description of the usage rights if
                    relevant.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Description
                </p>
            </td>
            <td valign="top">
                <p>
                    A brief description of the resource.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Abstract
                </p>
            </td>
            <td valign="top">
                <p>
                    An abstract of the content of the resource.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Table of Contents
                </p>
            </td>
            <td valign="top">
                <p>
                    Use the Table of Contents element to list all sections of a report, questionnaire, or other document. When copying a table of contents from
                    another file into a project, pay close attention to the formatting as tabs, indents, and fonts may not be preserved. Because the text
                    cannot be formatted, adopting strategies such as placing chapter titles in capital letters can help keep a table of contents organized.
                    Including page numbers is not crucial.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Subjects
                </p>
            </td>
            <td valign="top">
                <p>
                    The key topics discussed in the resource can be listed in the Subjects element. Although the IHSN Resource Template does not include a
                    controlled vocabulary for this element, organizations may opt to modify the template and establish a set list of subjects which all of
                    their projects should use when documenting studies.
                </p>
            </td>
			</tr>
		</tbody>
		</table>