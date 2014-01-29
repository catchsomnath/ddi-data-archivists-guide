================
Creating variable groups
================

Variable groups are optional, but will help organize the data for the user into specific subject of use categories. This will be particularly useful to the user in the case of data files that contain many variables and are not organized by topic (some flat files contain hundreds or even thousands of variables). 

The Toolkit allows you to group variables found in various separate data files. For example, education data may be found in various locations and the disparate variables grouped together. Also, a same variable can belong to more than one group.

Variable groups are “virtual”. The variables themselves are not moved or grouped. They remain untouched in the data files.

In the final output of the Toolkit (CD-ROM of website), the variable groups will appear under a menu item “Data dictionary”. The only reason for grouping variables is to allow users to easily locate variables related to their topic of interest. If your dataset contains very few variables, there is no justification for grouping them.

If you decide to create variable groups (and sub-groups if needed), make sure that ALL variables in the dataset belong to at least one group.

Variable groups also have their own DDI elements which include Type, Label, Text, Definition, Universe, and Notes. These elements are optional and will in most cases be left empty.

.. raw:: html

		<table border="1" cellpadding="0" cellspacing="0">
		<tbody>
        <tr>
            <td valign="top">
                <p>
                    Type
                </p>
            </td>
            <td valign="top">
                <p>
                    This is a controlled vocabulary field. It best identifies the manner the variables are grouped together. This field is optional.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Label
                </p>
            </td>
            <td valign="top">
                <p>
                    The label used to identify the group should be clear and relate to the type chosen. If these are grouped by subject, then the subject
                    should be clearly stated etc.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Text
                </p>
            </td>
            <td valign="top">
                <p>
                    Include additional text to clarify the reason or purpose for grouping the variables. This field is optional.
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
                    This optional field is used to define the variable group.
                </p>
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
                    This optional field defines the universe relevant to the selected grouped variables. The variables for example can be grouped as “Fertility
                    Data” and the universe restricted to women between the ages of 15-49.
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
                    Additional space for further optional explanatory notes.
                </p>
            </td>
        </tr>
    </tbody>
</table>