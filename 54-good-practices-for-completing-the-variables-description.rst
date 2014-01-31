===============
5.4. Good practices for completing the Variables Description
===============

The Variable Description is the section of the DDI document that provides detailed information on each variable.

.. raw:: html

		<table>
	    <tbody>
        <tr>
            <td valign="top">
                <p>
                    Variable Names
                </p>
            </td>
            <td valign="top">
                <p>
                    These are the names given to the variables. Ideally, the variable names should be a maximum of 8 characters, and use a logical naming
                    convention (e.g., section (S) and question (Q) numbers to name the question). If the variable names do not follow these principles, DO NOT
                    CHANGE THE VARIABLE NAMES IN THE TOOLKIT, but make recommendations to the data processor for consideration for future surveys.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Variable Labels
                </p>
            </td>
            <td valign="top">
                <p>
                    All variables should have a label that
                </p>
                <ul>
					<li>Provides the item or question number in the original data collection instrument (unless item number serves as the variable name)</li>
					<li>Provides a clear indication of what the variable contains</li>
					<li>Provides an indication of whether the variable is constructed from other items</li>
                
				<P>Recommendations: </p>
                <ul>
                    <li>Do not use ALL CAPS in labels.</li>
					<li>Make sure that different variables have different labels (avoid duplicate labels). The IHSN Toolkit provides a tool to check availability and unicity of variable labels (see Tools &gt; Validate Variable).
					<li>For expenditure or income: indicating the currency and period of reference is crucial (e.g. "Annual per capita real expenditure in local currency" </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Width, StartCol, Endcol
                </p>
            </td>
            <td valign="top">
                <p>
                    When you import your data files from Stata or SPSS, the information on StartCol and EndCol will be empty. It is crucial to add this
                    information, in order to allow users to export the data to ASCII fixed format. To do so, use the "Variables &gt; Resequence" command in the
                    Toolkit, for each data file.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Categories
                </p>
            </td>
            <td valign="top">
                <p>
                    Variable categories are the lists of codes (and their meaning) that apply to the variable. The Toolkit imports categories and their labels
                    from the source data files (SPSS, Stata).
                </p>
                <p>
                    If necessary, add/edit the codes. Use the Documentation &gt; Create categories from statistics if the source dataset did not include value
                    labels (e,g., when imported from ASCII). Make sure the categories are not hierarchical, and do not include codes for "Missing". The codes
                    for Missing must be specified in the "Missing data" field. If you fail to do that, the summary statistics (mean, standard deviation, etc)
                    will be calculated including the missing code, which will be considered as a valid value.
                </p>
                
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Data type
                </p>
            </td>
            <td valign="top">
                <p>
                    Four types of variables are recognized by the Toolkit:
                </p>
                <ul>
                    <li>Numeric: <em>Numeric variables are used to store any number, integer or floating point (decimals).</em>
                <li>Fixed string:
                    <em>
                        A fixed string variable has a predefined length (default length is 8 but it can range from 1 to 255 characters in length) which enables the publisher to handle this data type more efficiently.
                    </em></li>
					<li>Dynamic string: <em>Dynamic string variables can be used to store open-ended questions.</em></li>
					<li>Date: <em>date variables stored in ISO format (YYYY-MM-DD?—should specify)</em></li>
                </ul>
                <p>
                    The data type is usually properly identified when the data is imported. It is important to avoid the use of string variables when this is not absolutely needed. Such issues must be taken care of before the data is imported in the Toolkit. See the section on "<a href="#_Gathering_and_preparing">Gathering and preparing the dataset</a>" above.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Measure
                </p>
            </td>
            <td valign="top">
                <p>
                    The Microdata Management Toolkit will allow you to define the measure of a variable as:
                </p>
                <ul>
                    <li>
                        <em>Nominal</em>
                        : variable with numeric assignations for responses; the number assigned to each response does not have a meaning by itself.
                    </li>
                </ul>
                <p>
                    <em>Example</em>
                    : Variable <em>sex</em>: 1 = Male, 2 = Female (the number does not have a meaning by itself; we could as well have assigned Male = 2 and
                    Female = 1). When variables are nominal, we can produce frequency tables by code, but calculating mean or standard deviation of the codes
                    would not make sense.
                </p>
                <ul>
                    <li>
                        <em>Ordinal</em>
                        : variable with numeric assignations and in a logical sequence. The absolute size of the number, or the difference between two numbers
                        has no meaning. But the sequence of the number matters.
                    </li>
                </ul>
                <p>
                    <em>Example</em>
                    : An example of an ordinal variable would be a variable indicating the level of satisfaction of the respondent, for example on a scale of 1
                    (very unsatisfied) to 5 (very satisfied).
                </p>
                <ul>
                    <li>
                        <em>Scale</em>
                        : continuous variables that have inherent and not categorical value. Examples of such variables include the age of the person, the
                        amount of income or expenditure, etc.
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Time variable
                </p>
            </td>
            <td valign="top">
                <p>
                    This is a check-box used to tag and identify variables used to define time.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Weight variable
                </p>
            </td>
            <td valign="top">
                <p>
                    This is a check box that is used to tag the weight variable. It is a good practice to include the weight variable with each data file that
                    is being archived. If it is included, the check box should be ticked.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Min
                </p>
                <p>
                    Max
                </p>
            </td>
            <td valign="top">
                <p>
                    Allows modifying the minimum value of a variable. For each variable where it makes sense, you should check that the Min and Max values are
                    correct. Remember: if a specific value is used for "Missing", this should not be included in the Min-Max range. For example, if codes 1 and
                    2 are used for Male and Female, and 9 for unknown sex, then the Min will be 1 and the Max will be 2. The code 9 must be listed in the
                    "Missing" codes (see below).
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Decimals
                </p>
            </td>
            <td valign="top">
                <p>
                    Defines the number of decimal places of a numeric variable type.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Implicit decimals
                </p>
            </td>
            <td valign="top">
                <p>
                    This check box is selected only when a fixed ASCII-type file is imported and the data file includes a decimal character. As the decimal
                    character also requires a space in the variable length assignation, it is important to check this box in order to assure proper alignment
                    of the data.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Missing data
                </p>
            </td>
            <td valign="top">
                <p>
                    Missing values are those values that are blank in a data file but should have been responses and are within the path or universe of the
                    questionnaire. Missing values should always be coded. Missing values should be differentiated from "not applicable" and zero (0) values.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Statistics Options
                </p>
            </td>
            <td valign="top">
                <p>
                    Various options exist for displaying and presenting summary information of the variable to the user or the person browsing the output.
                    Summary statistics are saved in the DDI document and become part of the metadata. It is therefore important to select the appropriate ones.
                </p>
                <ul>
                    <li>For nominal variables you want to be sure that the categories are well defined and that some of the summary statistics are not displayed(such as means and standard deviations.
                <li>For ordinal values, you want to be sure that the categories are displayed if they are required. Not all ordinal values will require a category. In some cases you may want to include some summary statistics such as mean and standard deviation.
                <li>For scale values, you do not want to define categories and you may want to include some summary statistics such as mean and standard deviation.
                </p>
                <p>
                    Make sure you do not include "Frequencies" for variables such as the household identification number or enumeration area. This would
                    produce a useless frequency table, that would considerably increase the size of your DDI file (in general, a very large DDI file–8 to 10Mb
                    or more– indicates such a problem).
                </p>
                <p>
                    Make sure also that you do not include meaningless summary statistics, such as the mean or standard deviation calculated on the codes used
                    for variable SEX.
                </p>
                <p>
                    Notes:
                </p>
                <ul>
                    <li>Summary statistics such as the mean or standard deviation are calculated using all valid values. If special codes are used to indicate
                    missing values, make sure they are declared in the "Missing" section. If not, they will be included in the calculations. For example, if
                    you use code 99999 for indicating missing values in a variable on household expenditure, code 99999 must be listed in the missing section
                    as follows:
                </li>
                
                <li>
                    If you modify information such as the categories or missing values, you must use the "Documentation > Update Statistics" command in
                    the Toolkit to refresh the summary statistics.
                </li>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Weights
                </p>
            </td>
            <td valign="top">
                <p>
                    The appropriate weight should be attached to the file and selected in this element. The weight should be well labelled.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Definition
                </p>
            </td>
            <td valign="top">
                <p>
                    This element provides a space to describe the variable in detail. Not all variables require definition. The following variables should
                    always be defined when available in a questionnaire:
                </p>
				<ul>
                <li>Household (attach this definition to the "household ID" variable</li>
                <li>Head of household (attach this definition to the variable "relationship to the head"</li>
                </ul><li>
                        Urban/rural
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Universe
                </p>
            </td>
            <td valign="top">
                <p>
                    The universe at the variable level reflects skip patterns within-records in a questionnaire. This information can typically be copy/pasted
                    from the survey questionnaire. Try to be as specific as possible. This information is very useful for the analyst.
                </p>
                <p>
                    In many cases, a block of variables will have the same universe (for example, a block of variables on education can all relate to the
                    "Population aged 6 to 24 year). The Toolkit allows you to select multiple variables and enter the universe information to all variables at
                    once.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Source of information
                </p>
            </td>
            <td valign="top">
                <p>
                    Enter information regarding who provided the information contained within the variable. In most cases, the source will be "Head of
                    household" or "Household member". But it may also be
                </p>
                <ul>
                    <li>GPS measure (for geographic position)</li>
					<li>Interviewer’s visual observation (for type of dwelling)</li>
					<li>Best informant in community</li>
					<li>Etc.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Concepts
                </p>
            </td>
            <td valign="top">
                <p>
                    Greater description on the nature of the variable can be placed in this element. For example this element can provide a clearer definition
                    for certain variables (i.e. a variable that provides information on whether a person is a household member). In the case of household
                    membership, a conceptual definition can be provided.
                </p>
                <p>
                    Example:
                </p>
                <p>
                    <em>
                        A household member is defined as any person who has been resident in the household for six months or more in a given year and takes
                        meals together OR by default the head of household, infants under 6 months, newly wedded couples etc.
                    </em>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Pre-question text
                </p>
                <p>
                    Literal question
                </p>
                <p>
                    Post-question text
                </p>
            </td>
            <td valign="top">
                <p> The <em>pre-question texts </em>are the instructions provided to the interviewers and printed in the questionnaire before the literal question. This does not apply to all variables. Do not confuse this with instructions provided in the interviewer’s manual. With this and the next two fields, one should be able to understand how the question was asked during the interview. See example below.
                </p>
                <p>
                    The <em>literal question</em> is the full text of the questionnaire as the enumerator is expected to ask it when conducting the interview.
                    This does not apply to all variables (it does not apply to derived variables).
                </p>
                <p>
					The <em>post-question texts</em> are instructions provided to the interviewers, printed in the questionnaire after the literal question</u>. Post-question can be used to enter information on skips provided in the
                    questionnaire. This does not apply to all variables. Do not confuse this with instructions provided in the interviewer’s manual. With this
                    and the next two fields, one should be able to understand how the question was asked during the interview. See example above.
                </p>
                <p>
                    Example: In the example below (extracted from a UNICEF-MICS standard questionnaire), we find a pre-question, a literal question and a
                    post-question.
                </p>
                
                <ul>
                    <li>
                        Pre-question: <em>Check age. If child is 3 years old or more, ask:</em>
                    </li>
                    <li>
                        Literal question:
                        <em>
                            Does (name) attend any organized learning or early childhood education programme, such as private or government facility, including
                            kindergarten or community child care?
                        </em>
                    </li>
                    <li>
                        Post-question: <em>If answer is 2 or 9 &gt; Goto next module</em>
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Interviewer Instruction
                </p>
            </td>
            <td valign="top">
                <p>
                    Copy/paste the instructions provided to the interviewers <u>in the interviewer’s manual</u>. In cases where some instructions relate to
                    multiple variables, repeat the information in all variables. The Toolkit allows you to select multiple variables and enter the information
                    to all these variables at once.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Imputation
                </p>
            </td>
            <td valign="top">
                <p>
                    The field is provided to record any imputation or replacement technique used to correct inconsistent or unreasonable data. It is
                    recommended that this field provide a summary of what was done and include a reference to a file in the external resources section.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Recoding and derivation
                </p>
            </td>
            <td valign="top">
                <p>
                    This element applies to data that were obtained by recoding collected variables, or by calculating new variables that were not directly
                    obtained from data collection. It is very important to properly document such variables. Poorly documented variables cannot (or should not)
                    be used by researchers. In cases where the recoding or derivation method was very simple, a full description can be provided here. For
                    example, if variable AGE_GRP was obtained by recoding variable S1Q3, we could simply mention
                    <em>
                        "Variable obtained by recoding the age in years provided in variable S1Q3 into age groups for years 0-4, 5-9, …, 60-64, 65 and over.
                        Code 99 indicates unknown age."
                    </em>
                </p>
                <p>
                    When the derivation method is more complex, provide here a reference to a document (and/or computer program) to be provided as an External
                    Resource. This will be the case for example for a variable "TOT_EXP" containing the household annual total expenditure, obtained from a
                    household budget survey. In such case, the information provided here could be:
                </p>
                <p>
                    <em>
                        "This variable provides the annual household expenditure. It was obtained by aggregating expenditure data on all goods and services,
                        available in sections 4 to 6 of the household questionnaire. It contains imputed rental values for owner-occupied dwellings. The values
                        have been deflated by a regional price deflator available in variable REG_DEF". All values are in local currency. Outliers have been
                        fixed. Details on the calculations are available in Appendix 2 of the Report on Data Processing, and in the Stata program
                        "aggregates.do" available in external resources."
                    </em>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Security
                </p>
            </td>
            <td valign="top">
                <p>
                    This field will be left empty in most cases. It can be used to identify variables that are direct identifiers of the respondents (or highly
                    identifying indirect identifiers), and that should not be released.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Notes
                </p>
            </td>
            <td valign="top">
                <p>
                    This element is provided in order to record any additional or auxiliary information related to the specific variable.
                </p>
            </td>
        </tr>
		</tbody>
		</table>
