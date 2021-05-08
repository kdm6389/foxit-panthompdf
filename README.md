# foxit-panthompdf
foxit panthompdf prepatched msi installer moded with ai17.1.1

Removed component
	-OCR (Google OCR is better so no point using this OCR, and Google has more language like hindi)
	-PDF A/E/X
	-ConnectedPDF (no point in collabrating PDF)
	-Manual (online avalable)
	-All Languae except (ENU)
	-Activation (since already activated)
	-FoxitUpdater (update can break patch, so disabled permanently)
	-Evernote Support (handlful user uses Evernote)
	-Panthom PDF Creator
	-Office, Word, Excel, Powerpoint, Visio, Plugin)
	-Ifilter/IndexingPDF
	-ShellExtenton for WOrd, Excel, Powertpoint.
	-Lots of useless plugin:
		del /f /q  ./plugins/ActionWizard.fpi
		del /f /q  ./plugins/BoxPlugin.fpi
		del /f /q  ./plugins/Browser.fpi
		del /f /q  ./plugins/CloudReading.fpi
		del /f /q  ./plugins/CommentsSummary.fpi
		del /f /q  ./plugins/ComparePDF.fpi
		del /f /q  ./plugins/docusign_plugin.fpi
		del /f /q  ./plugins/DropboxPlugin.fpi
		del /f /q  ./plugins/Dwg2Pdf.fpi
		del /f /q  ./plugins/FoxitAccountManagement.fpi
		del /f /q  ./plugins/FoxitArchiveConnector.fpi
		del /f /q  ./plugins/FRMSPlgV2.fpi
		del /f /q  ./plugins/FXCrypto32.dll
		del /f /q  ./plugins/FXCrypto64.dll
		del /f /q  ./plugins/GoogleDrivePlugin.fpi
		del /f /q  ./plugins/IntegrateWithSP.fpi
		del /f /q  ./plugins/NdOffice.fpi
		del /f /q  ./plugins/NetDocuments.fpi
		del /f /q  ./plugins/OneDrivePlugin.fpi
		del /f /q  ./plugins/OpenText.fpi
		del /f /q  ./plugins/ShareReviewPlugin.fpi
		del /f /q  ./plugins/Subscribe.fpi
		del /f /q  ./plugins/U3DBrowser.fpi
		del /f /q  ./plugins/Updater.fpi
		del /f /q  ./plugins/WorkSite.fpi
		del /f /q  ./plugins/EgnytePlugin*
		del /f /q  ./plugins/FRMSPlgV2*
		del /f /q  ./plugins/OpenText*
		del /f /q  ./plugins/Worldox*

Left component:
	Viwer/Editor (mandatory component) 
	Spell
	PDF Creator (combine, convert) to ShellExtention
	PDF printer
  
  

No need to activate / Already activated for life time. 
