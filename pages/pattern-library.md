---
permalink: pattern-library/
layout: default
title: City of Lexington Content Guide
---

<div class="panel panel-default panel-example">
   <div class="panel-heading">
    [Draft] Pattern library for lexingtonky.gov
   </div>
   <div class="panel-body">
    It is based on the <a href="http://bootstrapdocs.com/v3.3.5/docs/getting-started/">Bootstrap 3.3.5 front-end framework</a>. If you need extra components, please use the markup and classes in the <a href="http://bootstrapdocs.com/v3.3.5/docs/components/">Bootstrap documentation</a>.
   </div>
</div>

<div class="panel panel-default panel-example">
   <div class="panel-heading">
      <h1 class="panel-title">Headings</h1>
   </div>
   <div class="panel-body">
      <h1>Heading 1</h1>
      <h2>Heading 2</h2>
      <h3>Heading 3</h3>
      <h4>Heading 4</h4>
      <h5>Heading 5</h5>
      <h6>Heading 6</h6>
   </div>
   <div class="panel-footer">
      <code>&lt;h1&gt;Heading 1&lt;/h1&gt;<br/>&lt;h2&gt;Heading 2&lt;/h2&gt;<br/>&lt;h3&gt;Heading 3&lt;/h3&gt;<br/>&lt;h4&gt;Heading 4&lt;/h4&gt;<br/>&lt;h5&gt;Heading 5&lt;/h5&gt;<br/>&lt;h6&gt;Heading 6&lt;/h6&gt;</code><br/></div>
</div>
<div class="panel panel-default panel-example">
   <div class="panel-heading">
      <h1 class="panel-title">Body text</h1>
   </div>
   <div class="panel-body">
      <p>Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nullam id dolor id nibh ultricies vehicula.</p>
      <p>Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec ullamcorper nulla non metus auctor fringilla. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Donec ullamcorper nulla non metus auctor fringilla.</p>
      <p>Maecenas sed diam eget risus varius blandit sit amet non magna. Donec id elit non mi porta gravida at eget metus. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.</p>
   </div>
   <div class="panel-footer">
      <code>&lt;p&gt;Nullam quis risus eget urna mollis ornare...&lt;/p&gt;  </code> </div>
</div>
<div class="panel panel-default panel-example">
   <div class="panel-heading">
      <h1 class="panel-title">Lead text</h1>
   </div>
   <div class="panel-body">
      <p class="lead">Use lead text when you want a paragraph or sentence to stand out.</p>
   </div>
   <div class="panel-footer">
      <code>&lt;p class=&quot;lead&quot;&gt;Use lead text when...&lt;/p&gt;</code> </div>
</div>
<div class="panel panel-default panel-example">
   <div class="panel-heading">
      <h1 class="panel-title">Link, strong and emphasis</h1>
   </div>
   <div class="panel-body">
      <p>This is just regular text without anything fancy.<br/><a target="_blank" href="#">This is a sample link</a><br/><strong>Strong text is what this is</strong><br/><em>This text is being emphasized</em><br/></p>
   </div>
   <div class="panel-footer">
      <code>&lt;p&gt;This is just regular text without anything fancy.<br/>&lt;a href=&quot;#&quot; target=&quot;_blank&quot;&gt;This is a sample link&lt;/a&gt;<br/>&lt;strong&gt;strong text is what this is&lt;/strong&gt;<br/>&lt;em&gt;this text is being emphasized&lt;/em&gt;&lt;br/&gt;&lt;/p&gt;</code>      </div>
</div>
<div class="panel panel-default panel-example">
   <div class="panel-heading">
      <h1 class="panel-title">Lists</h1>
   </div>
   <div class="panel-body">
      <div class="row">
         <div class="col-sm-6">
            <p>
               <b>Unordered</b></p>
            <ul>
               <li>Lorem ipsum dolor sit amet</li>
               <li>Consectetur adipiscing elit</li>
               <li>Integer molestie lorem at massa</li>
               <li>Facilisis in pretium nisl aliquet</li>
               <li>Nulla volutpat aliquam velit
                  <ul>
                     <li>Phasellus iaculis neque</li>
                     <li>Purus sodales ultricies</li>
                     <li>Vestibulum laoreet porttitor sem</li>
                  </ul>
               </li>
            </ul>
         </div>
         <div class="col-sm-6">
            <p>
               <b>Ordered</b></p>
            <ol>
               <li>Lorem ipsum dolor sit amet</li>
               <li>Consectetur adipiscing elit</li>
               <li>Integer molestie lorem at massa</li>
               <li>Facilisis in pretium nisl aliquet</li>
               <li>Nulla volutpat aliquam velit</li>
               <li>Faucibus porta lacus fringilla vel</li>
               <li>Aenean sit amet erat nunc</li>
               <li>Eget porttitor lorem</li>
            </ol>
         </div>
      </div>
   </div>
   <div class="panel-footer">
      <code>&lt;ul&gt;<br/>&lt;li&gt;...&lt;/li&gt;<br/>&lt;/ul&gt;<br/><br/>&lt;ol&gt;<br/>&lt;li&gt;...&lt;/li&gt;<br/>&lt;/ol&gt;</code> </div>
</div>
<div class="panel panel-default panel-example">
   <div class="panel-heading">
      <h1 class="panel-title">Table</h1>
   </div>
   <div class="panel-body">
      <ul>
         <li>Use<code>.table</code> for basic table styling.</li>
         <li>Use<code>.table-striped</code> to add zebra-striping to any table row.</li>
         <li>Use
            <code>.table-bordered</code> to add borders on all sides of the table and cells.</li>
         <li>Use
            <code>.table-condensed</code> to make tables more compact.</li>
      </ul>
      <p>You can add&#160;a combination of any of these classes to a table. In the example the classes
         <code>.table</code>,
         <code>.table-striped</code> and
         <code>.table-condensed</code> are being used.</p>
      <table class="table table-condensed table-striped">
         <caption>Table Caption</caption>
         <thead>
            <tr>
               <th>#</th>
               <th>Column heading</th>
               <th>Column heading</th>
               <th>Column heading</th>
            </tr>
         </thead>
         <tbody>
            <tr>
               <td>1</td>
               <td>Column content</td>
               <td>Column content</td>
               <td>Column content</td>
            </tr>
            <tr>
               <td>2</td>
               <td>Column content</td>
               <td>Column content</td>
               <td>Column content</td>
            </tr>
            <tr>
               <td>3</td>
               <td>Column content</td>
               <td>Column content</td>
               <td>Column content</td>
            </tr>
         </tbody>
      </table>
   </div>
   <div class="panel-footer">
      <code> &lt;table class=&quot;table table-condensed table-striped&quot;&gt;...&lt;/table&gt;</code> </div>
</div>
<div class="panel panel-default panel-example">
   <div class="panel-heading">
      <h1 class="panel-title">Alerts</h1>
   </div>
   <div class="panel-body">
      <div role="alert" class="alert alert-success">
         <strong>Well done!</strong> You successfully read this important alert message. </div>
      <div role="alert" class="alert alert-info">
         <strong>Heads up!</strong> This alert needs your attention, but it&#39;s not super important. </div>
      <div role="alert" class="alert alert-warning">
         <strong>Warning!</strong> Better check yourself, you&#39;re not looking too good. </div>
      <div role="alert" class="alert alert-danger">
         <strong>Oh snap!</strong> Change a few things up and try submitting again.</div>
   </div>
   <div class="panel-footer">
      <code> &lt;div class=&quot;alert alert-success&quot; role=&quot;alert&quot;&gt;...&lt;/div&gt;<br/>&lt;div class=&quot;alert alert-info&quot; role=&quot;alert&quot;&gt;...&lt;/div&gt;<br/>&lt;div class=&quot;alert alert-warning&quot; role=&quot;alert&quot;&gt;...&lt;/div&gt;<br/>&lt;div class=&quot;alert alert-danger&quot; role=&quot;alert&quot;&gt;...&lt;/div&gt; </code> </div>
</div>
<div class="panel panel-default panel-example">
   <div class="panel-heading">
      <h1 class="panel-title">Wells</h1>
   </div>
   <div class="panel-body">
      <ul>
         <li>Use
            <code>.well-sm</code> for a smaller well.</li>
         <li>Use
            <code>.well-lg</code> for a larger well.</li>
      </ul>
      <div class="well"> Look, I&#39;m in a well! </div>
   </div>
   <div class="panel-footer">
      <code>&lt;div class=&quot;well&quot;&gt;...&lt;/div&gt;</code> </div>
</div>
<div class="panel panel-default panel-example">
   <div class="panel-heading">
      <h3 class="panel-title">Tabs</h3>
   </div>
   <div class="panel-body">
      <ul role="tablist" class="nav nav-tabs">
         <li class="active" role="presentation">
            <a target="_blank" aria-expanded="true" data-toggle="tab" role="tab" aria-controls="home" href="#home">Home</a></li>
         <li role="presentation">
            <a target="_blank" aria-expanded="false" data-toggle="tab" role="tab" aria-controls="profile" href="#profile">Profile</a></li>
      </ul>
      <div class="tab-content">
         <div id="home" class="tab-pane active" role="tabpanel">
            <p>This is the content for the first Home tab.</p>
         </div>
         <div id="profile" class="tab-pane" role="tabpanel">
            <p>This is the content for the second Profile tab.</p>
         </div>
      </div>
   </div>
   <div class="panel-footer">
      <code>&lt;ul class=&quot;nav nav-tabs&quot; role=&quot;tablist&quot;&gt;<br/>&#160; &#160;&lt;li role=&quot;presentation&quot; class=&quot;active&quot;&gt;<br/>&#160; &#160; &#160; &lt;a href=&quot;#home&quot; aria-controls=&quot;home&quot; role=&quot;tab&quot; data-toggle=&quot;tab&quot; aria-expanded=&quot;true&quot;&gt;Home&lt;/a&gt;<br/>&#160; &#160;&lt;/li&gt;<br/>&#160; &#160;&lt;li role=&quot;presentation&quot;&gt;<br/>&#160; &#160; &#160; &lt;a href=&quot;#profile&quot; aria-controls=&quot;profile&quot; role=&quot;tab&quot; data-toggle=&quot;tab&quot; aria-expanded=&quot;false&quot;&gt;Profile&lt;/a&gt;<br/>&#160; &#160;&lt;/li&gt;<br/>&lt;/ul&gt;<br/><br/>&lt;div class=&quot;tab-content&quot;&gt;<br/>&#160; &#160;&lt;div role=&quot;tabpanel&quot; class=&quot;tab-pane active&quot; id=&quot;home&quot;&gt;...&lt;/div&gt;<br/>&#160; &#160;&lt;div role=&quot;tabpanel&quot; class=&quot;tab-pane&quot; id=&quot;profile&quot;&gt;...&lt;/div&gt;<br/>&lt;/div&gt;</code></div>
</div>
<div class="panel panel-default panel-example">
   <div class="panel-heading">
      <h3 class="panel-title">Accordions</h3>
   </div>
   <div class="panel-body">
      <div aria-multiselectable="true" role="tablist" id="accordion" class="panel-group">
         <div class="panel panel-default">
            <div class="panel-heading">
               <h4 class="panel-title">
                  <a target="_blank" aria-expanded="true" data-parent="#accordion" data-toggle="collapse" href="#collapseOne"> Collapsible Group Item #1 </a> </h4>
            </div>
            <div aria-expanded="true" id="collapseOne" class="panel-collapse collapse in">
               <div class="panel-body">Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven&#39;t heard of them accusamus labore sustainable VHS.</div>
            </div>
         </div>
         <div class="panel panel-default">
            <div class="panel-heading">
               <h4 class="panel-title">
                  <a target="_blank" aria-expanded="false" class="collapsed" data-parent="#accordion" data-toggle="collapse" href="#collapseTwo"> Collapsible Group Item #2 </a> </h4>
            </div>
            <div aria-expanded="false" id="collapseTwo" class="panel-collapse collapse" style="height: 0px;">
               <div class="panel-body">Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven&#39;t heard of them accusamus labore sustainable VHS.</div>
            </div>
         </div>
         <div class="panel panel-default">
            <div class="panel-heading">
               <h4 class="panel-title">
                  <a target="_blank" aria-expanded="false" class="collapsed" data-parent="#accordion" data-toggle="collapse" href="#collapseThree"> Collapsible Group Item #3</a></h4>
            </div>
            <div aria-expanded="false" id="collapseThree" class="panel-collapse collapse" style="height: 0px;">
               <div class="panel-body">Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven&#39;t heard of them accusamus labore sustainable VHS.</div>
            </div>
         </div>
      </div>
   </div>
   <div class="panel-footer">
      <code>&lt;div class=&quot;panel-group&quot; id=&quot;accordion&quot; role=&quot;tablist&quot; aria-multiselectable=&quot;true&quot;&gt;<br/>&#160; &#160;&lt;div class=&quot;panel panel-default&quot;&gt;<br/>&#160; &#160; &#160;&#160;&lt;div class=&quot;panel-heading&quot; role=&quot;tab&quot; id=&quot;headingOne&quot;&gt;<br/>&#160; &#160; &#160; &#160; &#160;&lt;h4 class=&quot;panel-title&quot;&gt; &lt;a role=&quot;button&quot; data-toggle=&quot;collapse&quot; data- &#160; &#160; &#160; &#160; &#160; &#160; &#160; &#160; &#160;parent=&quot;#accordion&quot; href=&quot;#collapseOne&quot; aria-expanded=&quot;true&quot; aria-controls=&quot;collapseOne&quot;&gt; Collapsible Group Item #1 &lt;/a&gt;&lt;/h4&gt;<br/>&#160; &#160;&#160; &#160;&lt;/div&gt;<br/>&#160; &#160; &#160;&#160;&lt;div id=&quot;collapseOne&quot; class=&quot;panel-collapse collapse in&quot; role=&quot;tabpanel&quot; aria-labelledby=&quot;headingOne&quot;&gt;<br/>&#160; &#160; &#160; &#160; &#160;&lt;div class=&quot;panel-body&quot;&gt; ... &lt;/div&gt;<br/>&#160; &#160; &#160;&#160;&lt;/div&gt;<br/>&#160; &#160;&lt;/div&gt;<br/>&#160; &#160;&lt;div class=&quot;panel panel-default&quot;&gt;<br/>&#160; &#160; &#160;&#160;&lt;div class=&quot;panel-heading&quot; role=&quot;tab&quot; id=&quot;headingTwo&quot;&gt;<br/>&#160; &#160; &#160; &#160; &#160;&lt;h4 class=&quot;panel-title&quot;&gt; &lt;a class=&quot;collapsed&quot; role=&quot;button&quot; data-toggle=&quot;collapse&quot; data-parent=&quot;#accordion&quot; href=&quot;#collapseTwo&quot; aria-expanded=&quot;false&quot; aria-controls=&quot;collapseTwo&quot;&gt; Collapsible Group Item #2 &lt;/a&gt;&lt;/h4&gt;<br/>&#160; &#160; &#160;&#160;&lt;/div&gt;<br/>&#160; &#160;&#160; &#160;&lt;div id=&quot;collapseTwo&quot; class=&quot;panel-collapse collapse&quot; role=&quot;tabpanel&quot; aria-labelledby=&quot;headingTwo&quot;&gt;<br/>&#160; &#160; &#160; &#160; &#160;&lt;div class=&quot;panel-body&quot;&gt; ... &lt;/div&gt;<br/>&#160; &#160; &#160;&#160;&lt;/div&gt;<br/>&#160; &#160;&lt;/div&gt;<br/>&#160; &#160;&lt;div class=&quot;panel panel-default&quot;&gt;<br/>&#160; &#160; &#160;&#160;&lt;div class=&quot;panel-heading&quot; role=&quot;tab&quot; id=&quot;headingThree&quot;&gt;<br/>&#160; &#160; &#160; &#160; &#160;&lt;h4 class=&quot;panel-title&quot;&gt; &lt;a class=&quot;collapsed&quot; role=&quot;button&quot; data-toggle=&quot;collapse&quot; data-parent=&quot;#accordion&quot; href=&quot;#collapseThree&quot; aria-expanded=&quot;false&quot; aria-controls=&quot;collapseThree&quot;&gt; Collapsible Group Item #3 &lt;/a&gt; &lt;/h4&gt;
         <br/>&#160; &#160; &#160;&#160;&lt;/div&gt;<br/>&#160; &#160; &#160;&#160;&lt;div id=&quot;collapseThree&quot; class=&quot;panel-collapse collapse&quot; role=&quot;tabpanel&quot; aria-labelledby=&quot;headingThree&quot;&gt;<br/>&#160; &#160;&#160; &#160; &#160; &lt;div class=&quot;panel-body&quot;&gt; ... &lt;/div&gt;<br/>&#160; &#160; &#160;&#160;&lt;/div&gt;<br/>&#160; &#160;&lt;/div&gt;<br/>&lt;/div&gt;</code></div>
</div>
