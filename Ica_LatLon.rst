stk.v.11.0
WrittenBy    STK_v11.2.0

BEGIN ReportStyle

BEGIN ClassId
	Class		Place
END ClassId

BEGIN Header
	StyleType		0
	Date		Yes
	Name		Yes
	IsHidden		No
	DescShort		No
	DescLong		No
	YLog10		No
	Y2Log10		No
	YUseWholeNumbers		No
	Y2UseWholeNumbers		No
	VerticalGridLines		No
	HorizontalGridLines		No
	AnnotationType		Spaced
	NumAnnotations		3
	NumAngularAnnotations		5
	ShowYAnnotations		Yes
	AnnotationRotation		1
	BackgroundColor		#ffffff
	ForegroundColor		#000000
	ViewableDuration		3600.000000
	RealTimeMode		No
	DayLinesStatus		1
	LegendStatus		1
	LegendLocation		1

BEGIN PostProcessor
	Destination	0
	Use	0
	Destination	1
	Use	0
	Destination	2
	Use	0
	Destination	3
	Use	0
END PostProcessor
	NumSections		1
END Header

BEGIN Section
	Name		Section 1
	ClassName		Place
	NameInTitle		No
	ExpandMethod		0
	PropMask		1
	ShowIntervals		No
	NumIntervals		0
	NumLines		1

BEGIN Line
	Name		Line 1
	NumElements		2

BEGIN Element
	Name		LLA State-Lat
	IsIndepVar		No
	Title		Lat
	NameInTitle		Yes
	Service		LLAState
	Element		Lat
	SumAllowedMask		0
	SummaryOnly		No
	DataType		0
	UnitType		19
	LineStyle		0
	LineWidth		0
	PointStyle		0
	PointSize		0
	FillPattern		0
	LineColor		#000000
	FillColor		#000000
	PropMask		0
	UseScenUnits		Yes
END Element

BEGIN Element
	Name		LLA State-Lon
	IsIndepVar		No
	Title		Lon
	NameInTitle		Yes
	Service		LLAState
	Element		Lon
	SumAllowedMask		0
	SummaryOnly		No
	DataType		0
	UnitType		20
	LineStyle		0
	LineWidth		0
	PointStyle		0
	PointSize		0
	FillPattern		0
	LineColor		#000000
	FillColor		#000000
	PropMask		0
	UseScenUnits		Yes
END Element
END Line
END Section

BEGIN LineAnnotations
END LineAnnotations
END ReportStyle

