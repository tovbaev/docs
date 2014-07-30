{{Page_Title}}
{{Flags
|State=In Progress
|Editorial notes=Add Category, Parent,  Children information and HTML information subsection. Complete Compatibility table.
|Checked_Out=Yes
|High-level issues=Needs Review
|Content=Incomplete, Examples Needed
}}
{{Standardization_Status|W3C Editor's Draft}}
{{API_Name}}
{{Summary_Section|Control which image resource a user agent presents to a user, based on media query and/or support for a particular image format.}}
{{Markup_Element
|DOM_interface=dom/HTMLPictureElement
|Content=The '''picture''' element (<code><picture></code>) addresses use cases that are left unaddressed by the srcset attribute, the most important being art direction. 

Other use cases, such as matching media features and media types and matching on supported image formats, are also addressed by this element.
}}
{{Examples_Section
|Not_required=No
|Examples={{Single Example
|Language=HTML
|Description=This example shows the basic usage of the picture element for responsive images and art direction.
|Code=<picture>
  &lt;source src="test_landscape_1@1x.jpg">
  &lt;source media="(min-width: 480px)" src="test_landscape_1@2x.jpg">
  &lt;source media="(min-width: 640px)" src="test_landscape_1@4x.jpg">
  &lt;!-- fallback img if picture is not supported -->
  <img src="test_landscape_1@2x.jpg" alt="Nymphenburg Castle in Munich during sunset">
</picture>
|LiveURL=http://responsiveimages.org/demos/basic-implementation/index.html
}}
}}
{{Notes_Section
|Usage=The picture element should be used when an image source exists in multiple densities, or when a responsive design dictates a somewhat different image on some types of screens (“art direction”).

The picture element is not a general replacement for the img element. When there is only a single image source, authors should just use the img element as usual, rather than cluttering their page with additional unnecessary syntax.
}}
{{Related_Specifications_Section
|Specifications={{Related Specification
|Name=Picture Specification (official, by RICG)
|URL=http://picture.responsiveimages.org/
|Status=Living Standard
}}
}}
{{Compatibility_Section
|Not_required=No
|Imported_tables=
|Desktop_rows=
|Mobile_rows=
|Notes_rows=
}}
{{See_Also_Section
|Topic_clusters=HTML
}}
{{Topics|DOM, HTML}}
{{External_Attribution
|Is_CC-BY-SA=No
|MDN_link=
|MSDN_link=
|HTML5Rocks_link=
}}