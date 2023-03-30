# Initial Plan

To get started understanding the necessary XML and XSLT details I'll start with the most simple case - truth table semantics.

This is in theory simple since the aim would be to define some XML elements and then the XSLT needed to turn that into an HTML table.

Some target XML for this might be:

    <tt>
    <variables values='2' 1='T' 2='F'>
    <var>P<val>T</val><value>F</value></var>
    <var>Q<value>T</value><value>F</value><value>T</value><value>F</value></variable>
    </variables>
    <operator type='and'>∨ <val>T</val></operator>
    </tt>
    
    <semanticProof>
    </semanticProof>
