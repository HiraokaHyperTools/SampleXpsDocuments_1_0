File Name:	SampleXpsDocuments_1_0.zip
Version:	1.0
License:	These sample documents are covered by the terms of the XPSTestFiles_EndUserLicenseAgreement.doc file included in this ZIP archive.
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

The sample documents in this ZIP archive were generated from a variety of sources, including those generated from
the Windows Presentation Foundation in WinFX, from Office 2007, from the Microsoft XPS Document Writer (MXDW), and a few
that were either hand-built from scratch or hand-modified from another source. They have been included to provide
you with a few documents that exercise a variety of features of the XML Paper Specification.

In addition, we have included a few high-quality documents in the Showcase directory to highlight some of the XPS advantages in terms of screen-to-print fidelity. We've also created some documents that are intended to fail, violating at least one conformance rule. These are in the ConformanceViolations directory.

Comments on various files is denoted following the file beginning with '--'.

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

These sample Test Files include:

MXDW/
	AlphaBlend.xps
	FullRun.xps
	OneBitBWG4_TIFF.xps
	PlgBlt.xps
	printarea01.xps
	printarea02.xps
	printarea03.xps
	printarea04.xps
	printarea05.xps
	printarea06.xps
	printarea07.xps
	printarea08.xps
	printarea09.xps
	printarea10.xps
	CalibriPoster.xps     	-- sample from the public Typography collection
	CambriaPoster.xps     	-- sample from the public Typography collection
	CandaraPoster.xps     	-- sample from the public Typography collection
	ConsolasPoster.xps     	-- sample from the public Typography collection
	ConstantiaPoster.xps     	-- sample from the public Typography collection
	CorbelPoster.xps     	-- sample from the public Typography collection
	TypeSamples.xps     	-- sample from the public Typography collection
	Properties/
		CoreProperty1.xps
		CoreProperty2.xps
	Thumbnail/
		Thumbnail.xps
	Zip64Interleaving/
		Zip64I_2FixedDoc_All_out.xps
		Zip64I_60FixedPage_out.xps
		Zip64I_Thumbnail_02_out.xps
	Zip64NonInterleaving/
		Zip64NI_2FixedDoc_All_out.xps
		Zip64NI_60FixedPage_out.xps
		Zip64NI_Thumbnail_02_out.xps
	ZipInterleaving/
		ZipI_2FixedDoc_All_out.xps
		ZipI_60FixedPage_out.xps
		ZipI_Thumbnail_02_out.xps
	ZipNonInterleaving/
		ZipNI_2FixedDoc_All_out.xps
		ZipNI_60FixedPage_out.xps
		ZipNI_Thumbnail_02_out.xps

Office2007/
	Office2007_24COLOR.xps
	Office2007_BULLETS.xps
	Office2007_COLORS.xps
	Office2007_EUROTEST.xps
	Office2007_Excel_AngledText.xps
	Office2007_Excel_digit_formats.xps
	Office2007_Excel_table.xps
	Office2007_Font_samples_UNICODE.xps
	Office2007_Page_direction.xps
	Office2007_PATTFILL.xps
	Office2007_Powerpoint_Drawing_Fills_Texture.xps
	Office2007_Powerpoint_Fills_Pattern.xps
	Office2007_Publisher_Kerning.xps
	Office2007_RGB_PNG_ROTATED.xps
	Office2007_Tables.xps
	Office2007_Word_ARTFILLGRADIENT.xps

WPF/
	WPF_base_content_not_paginated_to_fit_printticket.xps
	WPF_BitmapsWithAlpha.xps
	WPF_colorTextPrint.xps
	WPF_FONT_004_no_embed.xps
	WPF_fontRaster.xps
	WPF_GlyphsLinGradScaleTransfTemplate.xps
	WPF_GlyphsRadGradTransfTemplate.xps
	WPF_LinkDocSeq.xps
	WPF_MultiImage_FlowDoc_WhiteText.xps
	WPF_one_print_ticket_content_not_paginated_to_fit_printticket.xps
	WPF_two_print_ticket_content_not_paginated_to_fit_printticket.xps
	WPF_WMPhotoImage_CMYKText.xps
	WPF_WMPhotoImage_RgbAlphaText.xps
	WPF_WMPhotoImage_RGBText.xps
	WPF_ZORDEER_003.xps
	WPF_ZTRANS_001.xps
	WPF_ZTRANS_001_DIGITALLY_SIGNED.xps

Handcrafted/
	0inDashArray.xps	-- <Path> stroked with dashes; a zero-length space is present in the DashArray
	AlternateContent.xps	-- Contains various <AlternateContents> elements; should display "1 2 3 4"
	AlternateContent2.xps	-- Contains <AlternateContents> as the root element
	Bezier.xps		-- Complex Path element that uses Bezier curves
	Borderless-duplex.xps	-- Print: Document should print in duplex mode; first page should be borderless
	Braces.xps		-- Tests escaping of '{' as first char; first <Glyphs> should render without brace, 2nd with
	Canvas_Opacity.xps	-- Contains various Canvas elements with different Opacity values. Precision of values not the test focus.
	CaretStops.xps		-- Viewer: Tests selection for <Glyphs> with CaretStops specified
	Clipping.xps		-- Contains vaious <Glyphs> elements with diferent Clip area values. 
	ClusterMap.xps 		-- In the presence of an Indices, consumers MUST use the cluster map for each codepoint in the UnicodeString that specifies a cluster map instead of using the codepoint from the UnicodeString
	ColorTransparency.xps	-- Contains overlapping semi-transparent <Path>s, each with a different color. 
	DoubleTransformation.xps	-- Contains <Path> containing a <PathGeometry>, both of which are transformed - test to make sure transformations are applied in the correct order
	Fill.xps		-- 11 <Glyphs> elements filled with different brushes
	FillingStrokes.xps	-- Contains various stroked <Path> elements, where each stroke is filled with a different brush
	FontRenderingEmSize.xps	-- Various <Glyphs> sizes, including one that is 0 and should be ignored
	GradientStops.xps	-- Tests when GradientStops Offset values fall outside [0.0..1.0]
	ImageBrush.xps		-- Various ImageBrushes that should render the same
	ImagePixelFormats.xps	-- Contains images with a wide variety of supported pixel formats
	Interleaved.xps		-- Contains a simple interleaved document
	InvisibleObjects.xps	-- Contains various invisible elements (and one visible <Glyphs>)
	IsSideWays_and_BidiLevel.xps	-- Illustrates combinations of IsSideways and BidiLevel attributes; should be viewable and selectable
	LinearGradient_SpreadMethod.xps	-- Demonstrates various SpreadMethod settings in linear gradients
	Mitered.xps		-- Demonstrates miter limits, including an extreme case
	MustUnderstand.xps	-- Demonstrates a document that should be rendered using MustUnderstand
	NamedColor.xps		-- Usage of named colors illustrated
	NestedVB.xps		-- VisualBrush that is deeply nested
	Non-corresponding_page_sizes.xps	-- Fixed pages whose Width and Height do not match the advisory values in PageContent
	Non-invertible_transform.xps	-- Contains a <Path> with a non-invertible RenderTransform that must not be rendered
	NUp.xps			-- Print: Test rendering all 3 pages on one page
	Path.Data.xps		-- Various equivalent mechanisms to render the visually-same <Path>s
	PNGplus.xps		-- Contains extra PNG chunks that should be safely ignored.
	Portrait-landscape.xps	-- Page 1 and 3 are portrait, page 2 is landscape, PrintTickets reflect proper printing info
	RadialGradientBrush.xps	-- Various Path elements filled with RadialGradientBrush brushes. 
	RadialGradientBrush2.xps	-- RadialGradientBrush with GradientOrigin outside the ellipse
	Relative_Commands_in_AbbrGeom.xps	-- Demonstrates usage of the abbreviated geometry syntax
	RenderTransforms.xps	-- Contains a vector graphic of a book. Illustrates transform usage.
	RenderTransform_on_Strokes.xps	-- Demonstration of a RenderTransform applied to a stroke
	ResourceDictionary.xps	-- Illustrates ResourceDictionary usage
	Shape.xps		-- Contains complex Path elements that draw the characters "*TEXT/text*"
	SolidColorBrush.xps	-- Various Path elements filled with SolidColorBrush brushes. 
	StartEndLineCaps.xps	-- Demonstrates different StrokeEndLineCaps values.
	StrokeDashOffset.xps	-- Demonstrates different StrokeDashOffset values.
	Strokes.xps		-- Contains various Path elements with different kinds of strokes. 
	StyleSimulations.xps	-- 4 glyphs: normal, sim italic, sim bold, sim bold/italic
	TileMode_with_Glyphs.xps	-- 3 Path elements filled with VisualBrush containing a Glyph, but different TileModes. 
	VB_scaling.xps		-- Path filled with a VisualBrush, containing a Glyphs element. Text should render crisply.
	WindowsMediaPhoto.xps	-- Various Windows Media Photo images.
	Xml_lang.xps		-- Viewer: Text with different xml:lang values.
	XPS_Examples.xps	-- Samples from the XPS Specification
	XPS_in_strokes.xps	-- Various complex Path elements. 
	Z-Order.xps		-- Contains text that goes "through" a hole in a Path. 
	Zero-radius.xps		-- RadialGradientBrush brush with its RadiusX set to 0 

	FontLicensingIntent/	-- These files demonstrate different font licensing intent flags in a custom font
		XPSTestFont_Edit_0x8.xps
		XPSTestFont_Edit_Bitmap_0x208.xps
		XPSTestFont_Edit_Bitmap_NoSub_0x308.xps
		XPSTestFont_Edit_NoSub_0x108.xps
		XPSTestFont_Install_0x0.xps
		XPSTestFont_Install_Bitmap_0x200.xps
		XPSTestFont_Install_Bitmap_NoSub_0x300.xps
		XPSTestFont_Install_NoSub_0x100.xps
		XPSTestFont_Restrict_Bitmap_0x202.xps
		XPSTestFont_Restrict_Bitmap_NoSub_0x302.xps
		XPSTestFont_Restrict_NoSub_0x102.xps
		XPSTestFont_Rstrc_0x2.xps

	PrinTicketPositions/	-- These files demonstrate a variety print ticket placements in a XPS file
		pt-d1p2-d2p1.xps
		pt-d2-d1p2.xps
		pt-d2-d3.xps
		pt-fds-d1p2.xps
		pt-fds-d3.xps
		pt-fds.xps

	RenderedDocs/  -- These files are all TIFF renderings of files above with the same name at 96 dpi
		0inDashArray.tif
		AlternateContent.tif
		AlternateContent2.tif
		Bezier.tif
		Borderless-duplex.tif
		Braces.tif
		Canvas_Opacity.tif
		Clipping.tif
		ColorTransparency.tif
		DoubleTransformation.tif
		Fill.tif
		FillingStrokes.tif
		FontRenderingEmSize.tif
		GradientStops.tif
		ImageBrush.tif
		Interleaved.tif
		InvisibleObjects.tif
		IsSideWays_and_BidiLevel.tif
		LinearGradient_SpreadMethod.tif
		Mitered.tif
		MustUnderstand.tif
		NestedVB.tif
		Non-corresponding_page_sizes.tif
		Non-invertible_transform.tif
		NUp.tif
		Path.Data.tif
		PNGplus.tif
		Portrait-landscape.tif
		RadialGradientBrush.tif
		RadialGradientBrush2.tif
		Relative_Commands_in_AbbrGeom.tif
		RenderTransforms.tif
		RenderTransform_on_Strokes.tif
		ResourceDictionary.tif
		Shape.tif
		SolidColorBrush.tif
		StartEndLineCaps.tif
		StrokeDashOffset.tif
		Strokes.tif
		StyleSimulations.tif
		TileMode_with_Glyphs.tif
		VB_scaling.tif
		Xml_lang.tif
		XPS_09_Examples.tif
		XPS_in_strokes.tif
		Z-Order.tif
		Zero-radius.tif

Showcase/  -- Variety of sample "nice" documents
	Outlook2007_Calendar.xps
	PRI019_WinHEC06.xps
	Windows_Vista_Product_Guide.xps
	XPS_and_Enterprises.xps

QualityLogicMinBar/ -- Minimum bar test documents provided by Quality Logic
	mb01.xps
	mb02.xps
	mb03.xps
	mb04.xps
	mb05.xps
	mb06.xps
	mb07.xps
	mb08.xps
	mb09.xps
	

ConformanceViolations/  -- All these documents violate one conformance rule. They should fail or generate an error.
	MarkupCompatibility/
		M1.1a.xps  -- Unrecognized element from a non-ignorable namespace
		M1.2a.xps  -- Unrecognized element from Markup Compatibility namespace
		M2.13a.xps -- ProcessContent attribute on an element without an Ignorable attribute
		M2.14a.xps -- ProcessContent referencing an element whose namespace is not also listed as Ignorable
		M2.17a.xps -- Xml:lang attribute on a ProcessContent element
		M2.20a.xps -- PreserveElements attribute with no matching Ignorable attribute
		M2.24a.xps -- PreserveAttributes attribute with no matching Ignorable attribute
		M2.27a.xps -- Non-understood and ignorable namespace also identified in the MustUnderstand attribute value
		M2.27b.xps -- Non-understood namespace identified in the MustUnderstand attribute value
		M2.30a.xps -- AlternateContent element with no Choice child elements
		M2.31a.xps -- AlternateContent element with multiple Fallback child elements
		M2.32a.xps -- AlternateContent element with Fallback child element occurring before Choice child element
		M2.33a.xps -- Nested AlternateContent elements
		M2.35a.xps -- AlternateContent element with unprefixed Ignorable attribute. Namespace identified in Ignorable attribute is used.
		M2.35b.xps -- AlternateContent element with unprefixed Ignorable attribute. Namespace identified in Ignorable attribute is not used.
		M2.36a.xps -- AlternateContent having unrecognized child element that is not ignored
		M2.41a.xps -- Choice element having unrecognized and non-ignored attribute
		M2.42a.xps -- Choice element having MustUnderstand attribute referencing bad namespace
		M2.43a.xps -- Xml:lang attribute on AlternateContent element
		M2.44a.xps -- Choice element missing Requires attribute
		M2.48a.xps -- Choice element having unprefixed attribute other than Requires
		M2.49a.xps -- Xml:lang attribute on Choice element
		M2.50a.xps -- Requires attribute referencing non-understood namespace
		M2.52a.xps -- Prefixed Requires attribute applied to Choice element
		M2.55a.xps -- Unprefixed attribute applied to a Fallback element
		M2.56a.xps -- Xml:lang attribute on Fallback element

	OpenPackagingConvetions/
		M1.1a.xps -- InvalidZip -  Simple Text with empty reference to fdseq and empty fdseq name in zip
		M1.1b.xps -- Simple Text without PARTNAME in fdseq
		M1.2a.xps -- Simple Text without FPAGE Content Type
		M1.2b.xps -- Simple Text without JPEG Content Type
		M1.3a.xps -- Simple Text with empty segment in PARTNAME in fdseq
		M1.5a.xps -- Simple Text PARTNAME with forward slash as last char
		M1.6a.xps -- Simple Text PARTNAME with nonpchar in fdseq with orig doc name
		M1.6b.xps -- Simple Text PARTNAME with nonpchar in fdseq
		M1.7a.xps -- Simple Text core prop contains fwd slash pct encode and reference also contains pct encode
		M1.7c.xps -- Simple Text PARTNAME contains '%/'
		M1.8a.xps -- Simple Text PARTNAME contains '%c'
		M1.10a.xps -- Simple Text PARTNAME only dot
		M1.11a.xps -- Simple Text Fixed Doc Seq Part contains content type part name
		M1.17a.xps -- Invalid comma token in content type
		M1.18a.xps -- Content Types Leading Whitespace
		M1.18b.xps -- Content Types LWS between type and subtype
		M1.20a.xps -- Simple Text Doc with Content Type including param
		M1.22a.xps -- Simple Text Content Types with ISO encoding
		M1.26a.xps -- Relationship Missing ID
		M1.26b.xps -- Relationship with invalid XML Identifier
		M1.26c.xps -- Relationships with duplicate IDs
		M1.27a.xps -- Relationship with missing Type
		M1.28a.xps -- Relationship with missing Target
		M2.5a.xps -- Content Type with duplicate default elements
		M2.5b.xps -- Content Type with duplicate override elements
		M2.6a.xps -- Content Type with Content Type but no Extension attrib
		M2.6b.xps -- Content Type with Extension but no Content Type attrib
		M2.7a.xps -- Content Type with Override with no ContentType attrib
		M2.7b.xps -- Content Type with Override with no PartName attrib
		M2.18a.xps -- Simple Text with Non-Interleaved as two consecutive parts
		M2.24a.xps -- Simple Text with fdseq converted to single dot char
		M3.1a.xps -- Simple Text Doc with core props relationship pointing to thumbnail
		M3.1b.xps -- Simple Text Doc with two core props relationships
		M3.2a.xps -- Simple Text Core Prop Part with Markup Compat
		M3.4a.xps -- Simple Text with dig sig containing 2 dig sig origin parts
		M3.4b.xps -- Simple Text with Dig Sig missing relationship to Dig Sig Origin
		M3.5a.xps -- Simple Text with Dig Sig with no rel from dig sig orig to dig sig part
		M3.6a.xps -- Simple Text with dig sig with no relationship to cert
		M3.7a.xps -- Simple Text with dig sig ref with bad fragment identifier
		M3.8a.xps -- Simple Text with dig sig with 2 Object Elements
		M3.9a.xps -- Simple Text with dig sig with Object containing PCDATA
		M3.9b.xps -- Simple Text with dig sig with Object containing Signature
		M3.9c.xps -- Simple Text with dig sig with Sig Value in Object Element
		M3.10a.xps -- Simple Text with dig sig with fragment ident after Content Type
		M3.10b.xps -- Simple Text with dig sig with fragment ident right after URI
		M3.10c.xps -- Simple Text with dig sig with reference to external part
		M3.11a.xps -- Simple Text with Dig sig with ref query content type with bad content
		M3.11b.xps -- Simple Text with Dig Sig with Ref query with missing Content Type
		M3.12a.xps -- Simple Text with Dig Sig with Content Type not case matching
		M3.12b.xps -- Simple Text with dig sig with mismatched Reference Content Type
		M3.13a.xps -- Simple Text with dig sig Reference with unknown XForm
		M3.14a.xps -- Simple Text with dig sig Relationships XForm without Canon XForm
		M3.15a.xps -- Simple Text with dig sig with Signature Prop with no Sig Time
		M3.16a.xps -- Simple Text with dig sig with no Objects
		M3.17a.xps -- Simple Text with dig sig Signed Info missing Ref
		M3.17b.xps -- Simple Text with dig sig signedinfo with ref to incorrect object
		M3.18a.xps -- Simple Text with dig sig with bad algorithm
		M3.20a.xps -- Simple Text with dig sig Reference with unknown XForm
		M3.21a.xps -- Simple Text with dig sig with Manifest Object with no DigestMethod
		M3.21b.xps -- Simple Text with dig sig with no DigestMethod in Package object
		M3.25a.xps -- Simple Text with dig sig with Time format not compat with w3c
		M3.26a.xps -- Simple Text with dig sig with value element not matching format
		M3.28a.xps -- Simple Text with dig sig relation xform after canon xform
		M3.29a.xps -- Simple Text with dig sig with Relation xform having SourceType with case sensitive mismatch
		M3.31a.xps -- Simple Text with dig sig with DigestValue in Object Ref Descendant mismatch
		M3.31b.xps -- Simple Text with dig sig with DigestValue in Object Ref Descendant too long.
		M3.32a.xps -- Simple Text with dig sig with Bad DigestValue in Signed Info - Too long
		M3.32b.xps -- Simple Text with dig sig with Bad DigestValue in Signed Info – Wrong
		M4.1a.xps -- Simple Text with bad URI reference
		M4.2a.xps -- Simple Text PARTNAME contains '%c'
		M4.3a.xps -- Simple Text with percent encoding
		M6.1a.xps -- Simple Text with mismatch filename length
		M6.2a.xps -- Simple Text with invalid file name length
		M6.4a.xps -- Simple Text with unsupported compression method
		M6.6a.xps -- Simple Text with general purpose bit flag specifying files are encrypted
		M6.7a.xps -- Simple Text with offset of central directory equal to unsigned int max
		M6.8a.xps -- Simple Text with Total number of entries in central directory more than maxint
		M7.2a.xps -- Simple Text DC with xml:lang attrib

	XPS/
		M1.2a.xps -- Package is not a zip archive, it’s plain text instead
		M2.3a.xps -- Missing FixedDocumentSequence part
		M2.3b.xps -- Missing fixedrepresentation relationship
		M2.3c.xps -- Two fixedrepresentation relationships
		M2.4a.xps -- Missing FixedDocument part
		M2.4b.xps -- No <DocumentReference> to a FixedDocument
		M2.5a.xps -- Missing FixedPage part
		M2.5b.xps -- No <PageContent> to FixedPage
		M2.6a.xps -- Missing Font Part
		M2.6b.xps -- Missing FontURI attribute
		M2.10a.xps -- Missing required resource relationship for Font in FixedPage
		M2.13a.xps -- Missing fixedrepresentation relationship
		M2.13b.xps -- Two fixedrepresentation relationships
		M2.14a.xps -- Fixedrepresentation relationship pointing to FixedDocucment
		M2.18a.xps -- Corrupt PNG image
		M2.25a.xps -- Corrupt TIF image
		M2.36a.xps -- FixedPage with 2 thumbnails
		M2.37a.xps -- FixedPage with TIF thumbnail
		M2.59a.xps -- Two PrintTickets related to FixedDocumentSequence
		M2.71a.xps -- DTD in Relationship markup
		M2.71b.xps -- DTD in Content_Types markup
		M2.71c.xps -- DTD in FixedPage markup
		M2.73a.xps -- Xml:id attribute in FixedPage markup
		M2.73b.xps -- Xsi:SchemaLocation attribute on <FixedPage> element
		M2.74a.xps -- <Path> having Fill attrib and <Path.Fill> child element
		M2.75a.xps -- Xml:space attribute on <FixedPage> element
		M2.75b.xps -- Xml:space attribute on <Path> element
		M2.76a.xps -- Invalid value for xml:lang attribute on <FixedPage> element
		M3.2a.xps -- <DocucmentReference> Source attribute pointing to Fixed Page instead of FixedDocucment
		M3.3a.xps -- Multiple <DocumentReference> elements pointing to same FixedDocument
		M3.5a.xps -- <PageContent> Source attrib pointing to FixedDocucment instead of FixedPage
		M3.6a.xps -- Multiple <PageContent> elements pointing to the same FixedPage from difference FixedDocuments
		M3.6b.xps -- Multiple <PageContent> elements pointing to same FixedPage (from the same FixedDocument)
		M4.3a.xps -- <PathGeometry> element with Figures attribute and <Path.Figure> child element
		M5.2a.xps -- <Glyphs> with empty UnicodeString attribute and no Indices attribute
		M5.2b.xps -- <Glyphs> with UnicodeString attribute that contains “{}” and no Indices attribute
		M5.4a.xps -- <Glyphs> with an Indices attribute that contains an invalid Glyph Index for the specified font
		M5.4b.xps -- <Glyphs> that has more entries in the indices attribute than the UnicodeString attribute
		M5.7a.xps -- <Glyphs> that has a UnicodeString attribute that starts with '{'
		M5.15a.xps -- <Glyphs> that has both BidiLevel and isSideways attributes
		M6.2a.xps -- <ImageBrush> with x:Key attribute not in a <ResourceDictionary> 
		M6.3a.xps -- <ImageBrush> that references a font part
		M7.5a.xps -- Remote resource dictionary that references another remote resource dictionary 
		M12.2a.xps -- 2 references to the same FixedDocument
		M12.3b.xps -- FixedPage that is referenced twice from the same FixedDocuments
		M12.5a.xps -- FixedDocumentSequence with two PrintTickets
		M12.7a.xps -- ContentType attribute containing a Parameter (ContentType=”image/jpeg;q=0”)

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=