
# MTF Elements

<dl class="dl"> 	 	  <dt class="dt dlterm" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__GUID-9FF675C7-8C5A-42C9-98AA-B0B8A480E9BF">&lt;concept&gt; 	  </dt>
 	  <dd class="dd">Primary element of a conceptGrp. Content is the entry number. 		 
<div class="tablenoborder"><table cellpadding="4" cellspacing="0" summary="" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__TABLE_5D52B71590EF4748B95E241A0F6EBAF2" class="table" frame="border" border="1" rules="all"><colgroup><col style="width:14.025245441795231%"><col style="width:85.97475455820476%"></colgroup><tbody class="tbody"> 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> syntax: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> 					  <pre class="pre codeblock"><code>&lt;concept &gt;  
  ui4 datatype 
&lt;/concept&gt; </code></pre>					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> content: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> ui4 datatype 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> order: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> Ignored when a datatype is specified. 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> parents: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> conceptGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> children: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> No children allowed when a datatype is specified. 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> attributes: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> 					  <em class="ph i">(none)</em> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> model: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> Treated as closed when a datatype is specified. 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> source: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> 					  <pre class="pre codeblock"><code>&lt;ElementType name="concept" content="textOnly" model="closed" dt:type="ui4"&gt;       &lt;description&gt;Primary element of a conceptGrp. Content is the entry number.&lt;/description&gt;
&lt;/ElementType&gt;</code></pre>					</td>
 				 </tr>
 			  </tbody>
</table>
</div>
 	  </dd>
 	  </dl><dl class="dl"> 	 	  <dt class="dt dlterm" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__GUID-4BB0AA8F-CE60-461A-A6CA-74237499FADE">&lt;conceptGrp&gt; 	  </dt>
 	  <dd class="dd">The container for one concept. A concept has concept-level, language-independent fields, and at least one language group, which contains at least one term. 		 
<div class="tablenoborder"><table cellpadding="4" cellspacing="0" summary="" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__TABLE_BD88459A0DBD440DB701FB9C59A95D68" class="table" frame="border" border="1" rules="all"><colgroup><col style="width:12.095400340715502%"><col style="width:8.517887563884157%"><col style="width:79.38671209540034%"></colgroup><tbody class="tbody"> 				 <tr class="row">					<td class="entry cellrowborder" rowspan="3" style="vertical-align:top;"> syntax: 					</td>
					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"><code class="ph codeph">&lt;conceptGrp&gt;</code> 					</td>
				 </tr>
				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;">many 					</td>
					<td class="entry cellrowborder" style="vertical-align:top;">					  <p class="p"> &lt;concept&gt; 					  </p>
					  <p class="p">[ &lt;system&gt; ] * 					  </p>
					  <p class="p">[ &lt;transacGrp&gt; ] * 					  </p>
					  <p class="p">[ &lt;descripGrp&gt; ] * 					  </p>
					  <p class="p"> &lt;languageGrp&gt; + 					  </p>
					</td>
 				 </tr>
 				 <tr class="row">					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"><code class="ph codeph">&lt;/conceptGrp&gt;</code> 					</td>
				 </tr>
				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> content: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> eltOnly 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> order: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> many 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> parents: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> mtf 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> children: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> concept, descripGrp, languageGrp, system, transacGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> attributes: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> 					  <em class="ph i">(none)</em> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> model: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> closed 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> source: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> 					  <pre class="pre codeblock"><code>&lt;ElementType name="conceptGrp" content="eltOnly" order="many" model="closed"&gt;              &lt;description&gt;The container for one concept. A concept has concept-level, 
  language-independent fields, and at least one language group, which 
  contains at least one term.
  &lt;/description&gt;           &lt;element type="concept" minOccurs="1" maxOccurs="1"/&gt;            &lt;!-- contains concept-level info and languages --&gt;&lt;element type="system" minOccurs="0" maxOccurs="*"/&gt;&lt;element type="transacGrp" minOccurs="0" maxOccurs="*"/&gt;&lt;element type="descripGrp" minOccurs="0" maxOccurs="*"/&gt;&lt;element type="languageGrp" minOccurs="1" maxOccurs="*"/&gt;
&lt;/ElementType&gt;
</code></pre> 					</td>
 				 </tr>
 			  </tbody>
</table>
</div>
 	  </dd>
 	  </dl><dl class="dl"> 	 	  <dt class="dt dlterm" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__GUID-90B8322C-1038-4806-85CE-2596D2B4A439">&lt;date&gt; 	  </dt>
 	  <dd class="dd">A date in ISO-8601:1988 format, as implemented by MSXML2. 		 
<div class="tablenoborder"><table cellpadding="4" cellspacing="0" summary="" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__TABLE_B9CE644580F3412AB9C24BD79E925DF5" class="table" frame="border" border="1" rules="all"><colgroup><col style="width:11.976047904191617%"><col style="width:88.02395209580838%"></colgroup><tbody class="tbody"> 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> syntax: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> 					  <pre class="pre codeblock"><code>&lt;date &gt;  
 dateTime datatype 
&lt;/date&gt; </code></pre>					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> content: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> dateTime datatype 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> order: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> Ignored when a datatype is specified. 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> parents: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> transacGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> children: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> No children allowed when a datatype is specified. 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> attributes: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> 					  <em class="ph i">(none)</em> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> model: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> Treated as closed when a datatype is specified. 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> source: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> 					  <pre class="pre codeblock"><code>&lt;ElementType name="date" content="textOnly" dt:type="dateTime" model="closed"&gt;       &lt;description&gt;A date in ISO-8601:1988 format, as implemented by MSXML2.&lt;/description&gt;
&lt;/ElementType&gt;
</code></pre>					</td>
 				 </tr>
 			  </tbody>
</table>
</div>
	  </dd>
 	  </dl><dl class="dl">		  <dt class="dt dlterm" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__GUID-DA1C4546-F6E8-4D75-8F5F-C487736D7546">&lt;descrip&gt; 	  </dt>
	  <dd class="dd">Contains a descriptive, free-text element like a definition or a subject field. Content is formatted text, and the tag can carry a link attribute (link to concept, term, subject tree, graphics file, URL).		 
<div class="tablenoborder"><table cellpadding="4" cellspacing="0" summary="" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__TABLE_DF03BD9489E946C6A3125B7A4E5A5A30" class="table" frame="border" border="1" rules="all"><colgroup><col style="width:14.326647564469914%"><col style="width:85.67335243553009%"></colgroup><tbody class="tbody"> 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> syntax: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;">					  <pre class="pre codeblock"><code>&lt;descrip  [ Clink = string ] 
 [ Glink = string ] 
 [ Plink = string ] 
 [ Slink = string ] 
 [ Tlink = string ] 
 [ type = string ] 
 [ Ulink = string ] 
&gt;   
(many) [  &lt;xref&gt; ] * 
 mixed content 
&lt;/descrip&gt; </code></pre> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> content: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> mixed 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> order: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> many (default) 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> parents: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> descripGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> children: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> xref 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> attributes: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> Clink, Glink, Plink, Slink, Tlink, type, Ulink 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> model: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> closed 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> source: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;">					  <pre class="pre codeblock"><code>&lt;ElementType name="descrip" content="mixed" model="closed"&gt;       &lt;description&gt;Contains a descriptive, free-text element like a definition 
  or a subject field. Content is formatted text, and the tag can carry a 
  link attribute (link to concept, term, subject tree, graphics file, URL).
  &lt;/description&gt;     &lt;element type="xref" minOccurs="0" maxOccurs="*"/&gt;     &lt;attribute type="type" required="yes"/&gt;     &lt;attribute type="Clink"/&gt;     &lt;attribute type="Glink"/&gt;
      &lt;attribute type="Plink"/&gt;     &lt;attribute type="Slink"/&gt;     &lt;attribute type="Tlink"/&gt;     &lt;attribute type="Ulink"/&gt;
&lt;/ElementType&gt;
</code></pre> 					</td>
 				 </tr>
 			  </tbody>
</table>
</div>
	  </dd>
	 </dl><dl class="dl">		  <dt class="dt dlterm" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__GUID-02EE8144-90A5-4800-9DD5-B80EA8932486">&lt;descripGrp&gt; 	  </dt>
	  <dd class="dd">Contains a descriptive element, and optionally a source, transactional info, and a note. 		 
<div class="tablenoborder"><table cellpadding="4" cellspacing="0" summary="" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__TABLE_C67DA8B018A348F4A907661185E05877" class="table" frame="border" border="1" rules="all"><colgroup><col style="width:12.285012285012284%"><col style="width:87.7149877149877%"></colgroup><tbody class="tbody"> 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> syntax: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;">					  <pre class="pre codeblock"><code>&lt;descripGrp &gt;  
       &lt;descrip 
many [ &lt;transacGrp&gt; ] * 
     [ &lt;descripGrp&gt; ] * 
&lt;/descripGrp&gt; </code></pre> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> content: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> eltOnly 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> order: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> many 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> parents: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> conceptGrp, descripGrp, languageGrp, termGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> children: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> descrip, descripGrp, transacGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> attributes: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> 					  <em class="ph i">(none)</em> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> model: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> closed 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> source: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;">					  <pre class="pre codeblock"><code>&lt;ElementType name="descripGrp" content="eltOnly" order="many" model="closed"&gt;        &lt;description&gt;Contains a descriptive element, and optionally a source, 
  transactional info, and a note.
  &lt;/description&gt;        &lt;element type="descrip" minOccurs="1" maxOccurs="1"/&gt;        &lt;element type="transacGrp" minOccurs="0" maxOccurs="*"/&gt;        &lt;element type="descripGrp" minOccurs="0" maxOccurs="*"/&gt;
&lt;/ElementType&gt;
</code></pre> 					</td>
 				 </tr>
 			  </tbody>
</table>
</div>
	  </dd>
	 </dl><dl class="dl">		  <dt class="dt dlterm" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__GUID-CA37A679-42E8-4CA2-AFEB-3AFBBEF0DEFA">&lt;language&gt; 	  </dt>
	  <dd class="dd">A language specifier. The type attribute holds the "name" of the language as specified in the database definition, the lang attribute the locale in the form "en_us".		 
<div class="tablenoborder"><table cellpadding="4" cellspacing="0" summary="" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__TABLE_EED80992A4CC42969D33B13351728919" class="table" frame="border" border="1" rules="all"><colgroup><col style="width:12.210012210012207%"><col style="width:87.78998778998778%"></colgroup><tbody class="tbody"> 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> syntax: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;">					  <pre class="pre codeblock"><code>&lt;language  
 [ lang = string ] 
 [ type = string ] 
/&gt;</code></pre> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> content: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> empty 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> order: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> seq 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> parents: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> languageGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> children: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> 					  <em class="ph i">(none)</em> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> attributes: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> lang, type 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> model: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> open (default) 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> source: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;">					  <pre class="pre codeblock"><code>&lt;ElementType name="language" content="empty" order="seq"&gt;       &lt;description&gt;A language specifier. The type attribute holds the "name" of the language
  as specified in the database definition, the lang attribute the locale in the form "en_us".
  &lt;/description&gt;       &lt;attribute type="type" required="yes"/&gt;       &lt;attribute type="lang" required="yes"/&gt;
&lt;/ElementType&gt;
</code></pre> 					</td>
 				 </tr>
 			  </tbody>
</table>
</div>
	  </dd>
	 </dl><dl class="dl">		  <dt class="dt dlterm" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__GUID-AC0444C5-86CF-45C3-9E87-0417240B844B">&lt;languageGrp&gt; 	  </dt>
	  <dd class="dd">The container for information about all terms in one language.		 
<div class="tablenoborder"><table cellpadding="4" cellspacing="0" summary="" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__TABLE_70B584E114344706819A28E8D9627AC0" class="table" frame="border" border="1" rules="all"><colgroup><col style="width:7.757951900698215%"><col style="width:11.016291698991465%"><col style="width:81.22575640031032%"></colgroup><tbody class="tbody"> 				 <tr class="row">					<td class="entry cellrowborder" rowspan="3" style="vertical-align:top;"> syntax: 					</td>
					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"><code class="ph codeph">&lt;languageGrp &gt;</code>					</td>
				 </tr>
				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;">many 					</td>
					<td class="entry cellrowborder" style="vertical-align:top;">					  <p class="p">&lt;language&gt; 					  </p>
					  <p class="p">[ &lt;transacGrp&gt; ] * 					  </p>
					  <p class="p">[ &lt;descripGrp&gt; ] * 					  </p>
					  <p class="p"> &lt;termGrp&gt; + 					  </p>
					</td>
 				 </tr>
				 <tr class="row">					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"><code class="ph codeph">&lt;/languageGrp &gt;</code>					</td>
				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> content: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> eltOnly 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> order: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> many 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> parents: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> conceptGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> children: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> descripGrp, language, termGrp, transacGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> attributes: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> 					  <em class="ph i">(none)</em> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> model: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> closed 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> source: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> 					  <pre class="pre codeblock"><code>&lt;ElementType name="languageGrp" content="eltOnly" order="many" model="closed"&gt;       &lt;description&gt;The container for information about all terms in one language.&lt;/description&gt;       &lt;element type="language" minOccurs="1" maxOccurs="1"/&gt;       &lt;element type="transacGrp" minOccurs="0" maxOccurs="*"/&gt;       &lt;element type="descripGrp" minOccurs="0" maxOccurs="*"/&gt;
       	&lt;element type="termGrp" minOccurs="1" maxOccurs="*"/&gt;
&lt;/ElementType&gt;
</code></pre>					</td>
 				 </tr>
 			  </tbody>
</table>
</div>
	  </dd>
	 </dl><dl class="dl">		  <dt class="dt dlterm" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__GUID-0E36A1EE-EF4F-468C-B6A2-3F27BBA70E9B">&lt;mtf&gt; 	  </dt>
	  <dd class="dd">The root node of an MTF document. A document must contain at least one concept.		 
<div class="tablenoborder"><table cellpadding="4" cellspacing="0" summary="" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__TABLE_30D989C28CB24132BDAD891C041FA295" class="table" frame="border" border="1" rules="all"><colgroup><col style="width:7.8231292517006805%"><col style="width:4.2517006802721085%"><col style="width:87.92517006802721%"></colgroup><tbody class="tbody"> 				 <tr class="row">					<td class="entry cellrowborder" rowspan="3" style="vertical-align:top;"> syntax: 					</td>
					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"><code class="ph codeph">&lt;mtf&gt;</code> 					</td>
				 </tr>
				 <tr class="row">					<td class="entry cellrowborder" style="vertical-align:top;">seg					</td>
					<td class="entry cellrowborder" style="vertical-align:top;">&lt; conceptGrp &gt; + 					</td>
				 </tr>
				 <tr class="row"> 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"><code class="ph codeph">&lt;/mtf &gt;</code> 					</td>
 				 </tr>
 				 <tr class="row">					<td class="entry cellrowborder" style="vertical-align:top;"> content: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> eltOnly 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> order: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> seq 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> parents: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> No parents found. This is probably the document element. 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> children: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> conceptGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> attributes: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> 					  <em class="ph i">(none)</em> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> model: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> closed 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> source: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;">					  <pre class="pre codeblock"><code>&lt;ElementType name="mtf" content="eltOnly" order="seq" model="closed"&gt;       &lt;description&gt;The root node of an MTF document. A document must contain at least one concept.
  &lt;/description&gt;       &lt;element type="conceptGrp" minOccurs="1" maxOccurs="*"/&gt;
&lt;/ElementType&gt;
</code></pre> 					</td>
 				 </tr>
 			  </tbody>
</table>
</div>
	  </dd>
	 </dl><dl class="dl">		  <dt class="dt dlterm" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__GUID-078B7D76-2137-4220-AFC7-4A9416BCBEDA">&lt;system&gt; 	  </dt>
	  <dd class="dd">Contains system-maintained information like the old entry class and the approval status of a concept, language or term. The type attribute can be one of "entryClass" and "status".		 
<div class="tablenoborder"><table cellpadding="4" cellspacing="0" summary="" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__TABLE_56FCF03979864F61BE89A44A8897D483" class="table" frame="border" border="1" rules="all"><colgroup><col style="width:20.703933747412005%"><col style="width:79.29606625258799%"></colgroup><tbody class="tbody"> 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> syntax: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> 					  <pre class="pre codeblock"><code>&lt;system  
  type = enumeration: entryClass | status  
&gt;   
  textOnly content 
&lt;/system&gt; </code></pre>					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> content: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> textOnly 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> order: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> many (default) 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> parents: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> conceptGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> children: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> No children allowed when content is textOnly. 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> attributes: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> type 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> model: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> closed 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> source: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> 					  <pre class="pre codeblock"><code>&lt;ElementType name="system" content="textOnly" model="closed"&gt;       &lt;description&gt;Contains system-maintained information like the old entry class 
  and the approval status of a concept, language or term. 
  The type attribute can be one of "entryClass" and "status".
  &lt;/description&gt;       &lt;AttributeType name="type" dt:type="enumeration" dt:values="entryClass status" required="yes"&gt;	            &lt;description&gt;A system tag can be of type entryClass (values 1-8, inherited from old MTW databases) 
    or type status (values: new, reviewed, approved).&lt;/description&gt;       &lt;/AttributeType&gt;       &lt;attribute type="type" required="yes"/&gt;
&lt;/ElementType&gt;
</code></pre> 					</td>
 				 </tr>
 			  </tbody>
</table>
</div>
	  </dd>
	 </dl><dl class="dl">		  <dt class="dt dlterm" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__GUID-D97255ED-B671-4B76-BB28-04BAB0DB5353">&lt;term&gt; 	  </dt>
	  <dd class="dd">Contains a term as plain text. Note: we have requests for storing formatted terms containing sub- and superscript for mathematical and chemical formulae. This should be decided soon, IMHO it's doable. 		 
<div class="tablenoborder"><table cellpadding="4" cellspacing="0" summary="" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__TABLE_E83922B5BB06477195B812144B78FEF3" class="table" frame="border" border="1" rules="all"><colgroup><col style="width:21.186440677966097%"><col style="width:78.81355932203388%"></colgroup><tbody class="tbody"> 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> syntax: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;">					  <pre class="pre codeblock"><code>&lt;term&gt;
   textOnly content 
&lt;/term&gt;
 </code></pre> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> content: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> textOnly 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> order: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> many (default) 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> parents: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> termGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> children: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> No children allowed when content is textOnly. 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> attributes: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> 					  <em class="ph i">(none)</em> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> model: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> closed 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> source: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> 					  <pre class="pre codeblock"><code>&lt;ElementType name="term" content="textOnly" model="closed"&gt;       &lt;description&gt;Contains a term as plain text. Note: we have requests for storing 
  formatted terms containing sub- and superscript for mathematical and chemical formulae. 
  This should be decided soon, IMHO it's doable.
  &lt;/description&gt;
&lt;/ElementType&gt;
</code></pre>					</td>
 				 </tr>
 			  </tbody>
</table>
</div>
	  </dd>
	 </dl><dl class="dl">		  <dt class="dt dlterm" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__GUID-3B2788DE-35AD-4395-AD89-7C4B6EFD997A">&lt;termGrp&gt; 	  </dt>
	  <dd class="dd">Groups one term and all its associated information, which can be descriptions, source references, notes, and transactional information. 		 
<div class="tablenoborder"><table cellpadding="4" cellspacing="0" summary="" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__TABLE_02A7D823E3FD47D9AFDA1F020B56189F" class="table" frame="border" border="1" rules="all"><colgroup><col style="width:13.432835820895525%"><col style="width:12.437810945273634%"><col style="width:74.12935323383086%"></colgroup><tbody class="tbody"> 				 <tr class="row">					<td class="entry cellrowborder" rowspan="3" style="vertical-align:top;"> syntax: 					</td>
					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"><code class="ph codeph">&lt;termGrp&gt;</code> 					</td>
				 </tr>
				 <tr class="row">					<td class="entry cellrowborder" style="vertical-align:top;">many					</td>
					<td class="entry cellrowborder" style="vertical-align:top;">					  <p class="p"> &lt;term&gt; 					  </p>
					  <p class="p">[ &lt;transacGrp&gt; ] * 					  </p>
					  <p class="p">[ &lt;descripGrp&gt; ] * 					  </p>
					</td>
				 </tr>
				 <tr class="row"> 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"><code class="ph codeph">&lt;/termGrp&gt;</code> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> content: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> eltOnly 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> order: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> many 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> parents: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> languageGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> children: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> descripGrp, term, transacGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> attributes: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> 					  <em class="ph i">(none)</em> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> model: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> closed 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> source: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> 					  <pre class="pre codeblock"><code>&lt;ElementType name="termGrp" content="eltOnly" order="many" model="closed"&gt;       &lt;description&gt;Groups one term and all its associated information, which can be 
  descriptions, source references, notes, and transactional information.
  &lt;/description&gt;       &lt;element type="term" minOccurs="1" maxOccurs="1"/&gt;       &lt;element type="transacGrp" minOccurs="0" maxOccurs="*"/&gt;       &lt;element type="descripGrp" minOccurs="0" maxOccurs="*"/&gt;
&lt;/ElementType&gt;
</code></pre>					</td>
 				 </tr>
 			  </tbody>
</table>
</div>
	  </dd>
	 </dl><dl class="dl">		  <dt class="dt dlterm" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__GUID-A8C3B07E-EB24-420E-9835-3757769BBFAA">&lt;transac&gt; 	  </dt>
	  <dd class="dd">Contains a transaction type and responsible person. The type can be one of origination, modification. The content of the tag is the textual representation of the associated person link (Plink), i.e., the person's user id. 		 
<div class="tablenoborder"><table cellpadding="4" cellspacing="0" summary="" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__TABLE_C5CAB79EC994443C9A0FEA947F9A17DD" class="table" frame="border" border="1" rules="all"><colgroup><col style="width:13.262599469496022%"><col style="width:86.73740053050398%"></colgroup><tbody class="tbody"> 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> syntax: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;">					  <pre class="pre codeblock"><code>&lt;transac  
[ Plink = string ] 
  type = enumeration: origination | modification  
&gt;  
 textOnly content 
&lt;/transac&gt; </code></pre> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> content: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> textOnly 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> order: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> many (default) 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> parents: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> transacGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> children: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> No children allowed when content is textOnly. 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> attributes: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> Plink, type 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> model: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> closed 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> source: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;">					  <pre class="pre codeblock"><code>&lt;ElementType name="transac" content="textOnly" model="closed"&gt;       &lt;description&gt;Contains a transaction type and responsible person. The type can be one
  of origination, modification. The content of the tag is the textual representation of 
  the associated person link (Plink), i.e., the person's user id. 
  &lt;/description&gt;       &lt;AttributeType name="type" dt:type="enumeration" dt:values="origination modification" required="yes"&gt;	            &lt;description&gt;A transac tag can be of type origination (the associated field has been created) 
    or type modification (the associated field has been modified).&lt;/description&gt;       &lt;/AttributeType&gt;       &lt;attribute type="type" required="yes"/&gt;       &lt;attribute type="Plink"/&gt;
&lt;/ElementType&gt;
</code></pre> 					</td>
 				 </tr>
 			  </tbody>
</table>
</div>
	  </dd>
	 </dl><dl class="dl">		  <dt class="dt dlterm" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__GUID-F604B5F6-ABEB-4334-99A2-22BA48B8B181">&lt;transacGrp&gt; 	  </dt>
	  <dd class="dd">Contains a transaction and date, and optionally a note. 		 
<div class="tablenoborder"><table cellpadding="4" cellspacing="0" summary="" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__TABLE_D3606C45025A4C6FB1B4937EE799CB88" class="table" frame="border" border="1" rules="all"><colgroup><col style="width:8.741522230595328%"><col style="width:7.5357950263752835%"><col style="width:83.72268274302938%"></colgroup><tbody class="tbody"> 				 <tr class="row">					<td class="entry cellrowborder" rowspan="3" style="vertical-align:top;"> syntax: 					</td>
					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"><code class="ph codeph">&lt;transacGrp&gt; 					  </code>					</td>
				 </tr>
				 <tr class="row">					<td class="entry cellrowborder" style="vertical-align:top;">many					</td>
					<td class="entry cellrowborder" style="vertical-align:top;">					  <p class="p">&lt;transac&gt; 					  </p>
					  <p class="p"> &lt;date&gt; 					  </p>
					</td>
				 </tr>
				 <tr class="row"> 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"><code class="ph codeph">&lt;/transacGrp&gt;</code> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> content: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> eltOnly 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> order: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> many 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> parents: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> conceptGrp, descripGrp, languageGrp, termGrp 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> children: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> date, transac 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> attributes: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> 					  <em class="ph i">(none)</em> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> model: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;"> closed 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> source: 					</td>
 					<td class="entry cellrowborder" colspan="2" style="vertical-align:top;">					  <pre class="pre codeblock"><code>&lt;ElementType name="transacGrp" content="eltOnly" order="many" model="closed"&gt;        &lt;description&gt;Contains a transaction and date, and optionally a note.&lt;/description&gt;        &lt;element type="transac" minOccurs="1" maxOccurs="1"/&gt;        &lt;element type="date" minOccurs="1" maxOccurs="1"/&gt;
&lt;/ElementType&gt;
</code></pre> 					</td>
 				 </tr>
 			  </tbody>
</table>
</div>
	  </dd>
	 </dl><dl class="dl">		  <dt class="dt dlterm" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__GUID-F4FEF137-0BE3-445F-9395-4C7E74D332E0">&lt;xref&gt; 	  </dt>
	  <dd class="dd">Contains a descriptive, free-text element like a definition or a subject field. Content is formatted text, and the tag can carry a link attribute (link to concept, term, subject tree, graphics file, URL). 		 
<div class="tablenoborder"><table cellpadding="4" cellspacing="0" summary="" id="GUID-A639447F-F42A-42F8-8945-72C00BBA3176__TABLE_EF56CF0F1E4A4B6B84FC85D499336230" class="table" frame="border" border="1" rules="all"><colgroup><col style="width:13.192612137203167%"><col style="width:86.80738786279683%"></colgroup><tbody class="tbody"> 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> syntax: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;">					  <pre class="pre codeblock"><code>&lt;xref  
 [ Tlink = string ] 
&gt; 
  textOnly content 
&lt;/xref&gt; </code></pre> 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> content: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> textOnly 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> order: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> many (default) 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> parents: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> descrip 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> children: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> No children allowed when content is textOnly. 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> attributes: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> Tlink 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> model: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;"> closed 					</td>
 				 </tr>
 				 <tr class="row"> 					<td class="entry cellrowborder" style="vertical-align:top;"> source: 					</td>
 					<td class="entry cellrowborder" style="vertical-align:top;">					  <pre class="pre codeblock"><code>&lt;ElementType name="xref" content="textOnly" model="closed"&gt;       &lt;description&gt;Contains a descriptive, free-text element like a definition 
  or a subject field. Content is formatted text, and the tag can carry a 
  link attribute (link to concept, term, subject tree, graphics file, URL).
  &lt;/description&gt;       &lt;attribute type="Tlink" required="yes"/&gt;
&lt;/ElementType&gt;
</code></pre> 					</td>
 				 </tr>
 			  </tbody>
</table>
</div>
	  </dd>
	 </dl>



**Parent topic:** [XML Schema: MTF](GUID-DFB95E09-CFE6-4C71-AC6B-54A7E2012999.html "This schema describes the following elements and attributes:")


