include $(GNUSTEP_MAKEFILES)/common.make

APP_NAME = MathEdit
MathEdit_OBJC_FILES = main.m \
	MATHAppDelegate.m MATHAccessoryWindowsOwner.m\
	MATHAccessoryWindowViews.m MATHDocument.m\
	MATHDocumentModelController.m MATHDocumentViewController.m\
	MATHSolver.m MATHSolverExpressionTagger.m MATHSolverScanner.m\
	MATHSolverSolutionTagger.m MATHSolverStyler.m\
	MATHSolverTextAttachment.m XPCrossPlatform.m XPDocument.m\
	XPRegularExpression.m NSUserDefaults+MathEdit.m\
	TestsIntegration.m TestsUnit.m

MathEdit_C_FILES = slre.c

MathEdit_HAS_RESOURCE_BUNDLE = yes
MathEdit_RESOURCE_FILES = English.lproj/WelcometoMathEdit.mtxt English.lproj/InfoPlist.strings English.lproj/Localizable.strings \
	Images/about-image-512.tiff Images/NeXTLogoMed.tiff\
	Images/TagLine.tiff Images/ThemeAuto.tiff\
	Images/ThemeDark.tiff Images/ThemeLight.tiff\
	TestsIntegration-DiskRep.txt\
	TestsIntegration-DisplayRep.rtf\
	TestsIntegration-SolvedRep.rtf\
	TestsIntegration-UnsolvedRep.rtf

include $(GNUSTEP_MAKEFILES)/application.make
