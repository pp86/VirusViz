# VirusViz

## Specification for external services
<p>Button for opening data in VirusViz :</p>

<code>
    <pre>&lt;a class="btn btn-lg" style="background-color: #009688; color:white;" target="_blank" href="..."&gt;
    &lt;img src="img/virusviz-logo.png" width="25px"/&gt;
    Open in VirusViz
&lt;a/>
   </pre>
</code>

The <code>href</code> attribute should redirect to the VirusViz service with the following <code>GET</code> parameters:

<table class="table">
    <tr>
        <th>Parameter</th>
        <th>Value (example)</th>
        <th>Description</th>
    </tr>
    <tr style="font-weight: 100;">
        <th><code>appName</code></th>
        <th>ViruSurf</th>
        <th>Name of the external application that wants to visualize data on VirusViz.</th>
    </tr>
    <tr>
        <th><code>dataURL</code></th>
        <th>http://www.geco.deib.polimi.it?resultId=1234</th>
        <th>URL of the JSON containing the data that should be visualized in VirusViz.</th>
    </tr>
    <tr>
        <th><code>appURL</code></th>
        <th>http://www.geco.deib.polimi.it/virusurf</th>
        <th>(optional) Address of the application.</th>
    </tr>

</table>
