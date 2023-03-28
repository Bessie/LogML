# Initial Plan

To get started understanding the necessary XML and XSLT details I'll start with the most simple case - truth table semantics.

This is in theory simple since the aim would be to define some XML elements and then the XSLT needed to turn that into an HTML table.

Some target XML for this might be:

    <semanticTable>
    <variables>
    <variable>P<value>T</value><value>F</value></variable>
    <variable>Q<value>T</value><value>F</value><value>T</value><value>F</value></variable>
    </variables>
    <functions>
    <function>P ∨ Q</function>
    <result>P ∨ Q<value>T</value><value>F</value><value>T</value><value>F</value></result>
    </functions>
    </semanticTable>
