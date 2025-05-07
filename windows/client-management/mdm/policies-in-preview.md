---
title: Configuration service provider preview policies
description: Learn more about configuration service provider (CSP) policies that are available for Windows Insider Preview.
ms.date: 05/02/2025
ms.topic: generated-reference
---

<!-- Auto-Generated CSP Document -->

# Configuration service provider policies in preview

[!INCLUDE [Windows Insider tip](includes/mdm-insider-csp-note.md)]

This article lists the policies that are applicable for Windows Insider Preview builds.

## AppDeviceInventory

- [TurnOffInstallTracing](policy-csp-appdeviceinventory.md#turnoffinstalltracing)
- [TurnOffAPISamping](policy-csp-appdeviceinventory.md#turnoffapisamping)
- [TurnOffApplicationFootprint](policy-csp-appdeviceinventory.md#turnoffapplicationfootprint)
- [TurnOffWin32AppBackup](policy-csp-appdeviceinventory.md#turnoffwin32appbackup)

## ApplicationManagement

- [AllowedNonAdminPackageFamilyNameRules](policy-csp-applicationmanagement.md#allowednonadminpackagefamilynamerules)
- [ConfigureMSIXAuthenticationAuthorizedDomains](policy-csp-applicationmanagement.md#configuremsixauthenticationauthorizeddomains)

## ClientCertificateInstall CSP

- [AttestPrivateKey](clientcertificateinstall-csp.md#userscepuniqueidinstallattestprivatekey)

## CloudDesktop CSP

- [EnablePhysicalDeviceAccessOnCtrlAltDel](clouddesktop-csp.md#userenablephysicaldeviceaccessonctrlaltdel)
- [EnablePhysicalDeviceAccessOnErrorScreens](clouddesktop-csp.md#userenablephysicaldeviceaccessonerrorscreens)
- [EnableBootToCloudSharedPCMode](clouddesktop-csp.md#deviceenableboottocloudsharedpcmode)

## Connectivity

- [DisableCrossDeviceResume](policy-csp-connectivity.md#disablecrossdeviceresume)
- [UseCellularWhenWiFiPoor](policy-csp-connectivity.md#usecellularwhenwifipoor)
- [DisableCellularSettingsPage](policy-csp-connectivity.md#disablecellularsettingspage)
- [DisableCellularOperatorSettingsPage](policy-csp-connectivity.md#disablecellularoperatorsettingspage)

## DeclaredConfiguration CSP

- [Document](declaredconfiguration-csp.md#hostcompletedocumentsdociddocument)
- [Abandoned](declaredconfiguration-csp.md#hostcompletedocumentsdocidpropertiesabandoned)
- [ConflictResolution](declaredconfiguration-csp.md#managementserviceconfigurationconflictresolution)

## DeliveryOptimization

- [DODisallowCacheServerDownloadsOnVPN](policy-csp-deliveryoptimization.md#dodisallowcacheserverdownloadsonvpn)
- [DOVpnKeywords](policy-csp-deliveryoptimization.md#dovpnkeywords)

## DeviceGuard

- [MachineIdentityIsolation](policy-csp-deviceguard.md#machineidentityisolation)

## DevicePreparation CSP

- [PageEnabled](devicepreparation-csp.md#pageenabled)
- [PageStatus](devicepreparation-csp.md#pagestatus)
- [PageErrorPhase](devicepreparation-csp.md#pageerrorphase)
- [PageErrorCode](devicepreparation-csp.md#pageerrorcode)
- [PageErrorDetails](devicepreparation-csp.md#pageerrordetails)
- [PageSettings](devicepreparation-csp.md#pagesettings)
- [ExecutionContext](devicepreparation-csp.md#bootstrapperagentexecutioncontext)
- [Progress](devicepreparation-csp.md#mdmproviderprogress)
- [MdmAgentInstalled](devicepreparation-csp.md#mdmprovidermdmagentinstalled)
- [RebootRequired](devicepreparation-csp.md#mdmproviderrebootrequired)

## Display

- [ConfigureMultipleDisplayMode](policy-csp-display.md#configuremultipledisplaymode)
- [SetClonePreferredResolutionSource](policy-csp-display.md#setclonepreferredresolutionsource)

## DMClient CSP

- [DiscoveryEndpoint](dmclient-csp.md#deviceproviderprovideridlinkedenrollmentdiscoveryendpoint)
- [Enabled](dmclient-csp.md#deviceproviderprovideridconfigrefreshenabled)
- [Cadence](dmclient-csp.md#deviceproviderprovideridconfigrefreshcadence)
- [PausePeriod](dmclient-csp.md#deviceproviderprovideridconfigrefreshpauseperiod)

## FileSystem

- [EnableDevDrive](policy-csp-filesystem.md#enabledevdrive)
- [DevDriveAttachPolicy](policy-csp-filesystem.md#devdriveattachpolicy)
- [ClfsAuthenticationChecking](policy-csp-filesystem.md#clfsauthenticationchecking)

## HealthAttestation CSP

- [AttestErrorMessage](healthattestation-csp.md#attesterrormessage)

## HumanPresence

- [ForceOnlookerDetection](policy-csp-humanpresence.md#forceonlookerdetection)
- [ForceOnlookerDetectionAction](policy-csp-humanpresence.md#forceonlookerdetectionaction)

## InternetExplorer

- [AllowLegacyURLFields](policy-csp-internetexplorer.md#allowlegacyurlfields)

## LanguagePackManagement CSP

- [Providers](language-pack-management-csp.md#installedlanguageslanguage-idproviders)
- [LanguageFeatures](language-pack-management-csp.md#installedlanguageslanguage-idlanguagefeatures)
- [Status](language-pack-management-csp.md#installlanguage-idstatus)
- [ErrorCode](language-pack-management-csp.md#installlanguage-iderrorcode)
- [CopyToDeviceInternationalSettings](language-pack-management-csp.md#installlanguage-idcopytodeviceinternationalsettings)
- [EnableLanguageFeatureInstallations](language-pack-management-csp.md#installlanguage-idenablelanguagefeatureinstallations)
- [StartInstallation](language-pack-management-csp.md#installlanguage-idstartinstallation)
- [SystemPreferredUILanguages](language-pack-management-csp.md#languagesettingssystempreferreduilanguages)

## LanmanServer

- [AuditClientDoesNotSupportEncryption](policy-csp-lanmanserver.md#auditclientdoesnotsupportencryption)
- [AuditClientDoesNotSupportSigning](policy-csp-lanmanserver.md#auditclientdoesnotsupportsigning)
- [AuditInsecureGuestLogon](policy-csp-lanmanserver.md#auditinsecureguestlogon)
- [AuthRateLimiterDelayInMs](policy-csp-lanmanserver.md#authratelimiterdelayinms)
- [EnableAuthRateLimiter](policy-csp-lanmanserver.md#enableauthratelimiter)
- [EnableMailslots](policy-csp-lanmanserver.md#enablemailslots)
- [MaxSmb2Dialect](policy-csp-lanmanserver.md#maxsmb2dialect)
- [MinSmb2Dialect](policy-csp-lanmanserver.md#minsmb2dialect)

## LanmanWorkstation

- [AuditInsecureGuestLogon](policy-csp-lanmanworkstation.md#auditinsecureguestlogon)
- [AuditServerDoesNotSupportEncryption](policy-csp-lanmanworkstation.md#auditserverdoesnotsupportencryption)
- [AuditServerDoesNotSupportSigning](policy-csp-lanmanworkstation.md#auditserverdoesnotsupportsigning)
- [EnableMailslots](policy-csp-lanmanworkstation.md#enablemailslots)
- [MaxSmb2Dialect](policy-csp-lanmanworkstation.md#maxsmb2dialect)
- [MinSmb2Dialect](policy-csp-lanmanworkstation.md#minsmb2dialect)
- [RequireEncryption](policy-csp-lanmanworkstation.md#requireencryption)

## LocalPoliciesSecurityOptions

- [InteractiveLogon_NumberOfPreviousLogonsToCache](policy-csp-localpoliciessecurityoptions.md#interactivelogon_numberofpreviouslogonstocache)
- [NetworkAccess_RemotelyAccessibleRegistryPaths](policy-csp-localpoliciessecurityoptions.md#networkaccess_remotelyaccessibleregistrypaths)
- [NetworkAccess_RemotelyAccessibleRegistryPathsAndSubpaths](policy-csp-localpoliciessecurityoptions.md#networkaccess_remotelyaccessibleregistrypathsandsubpaths)
- [UserAccountControl_BehaviorOfTheElevationPromptForAdministratorProtection](policy-csp-localpoliciessecurityoptions.md#useraccountcontrol_behavioroftheelevationpromptforadministratorprotection)
- [UserAccountControl_TypeOfAdminApprovalMode](policy-csp-localpoliciessecurityoptions.md#useraccountcontrol_typeofadminapprovalmode)

## MixedReality

- [AutoUnlock](policy-csp-mixedreality.md#autounlock)
- [ConfigureSharedAccount](policy-csp-mixedreality.md#configuresharedaccount)
- [ConfigureDeviceStandbyAction](policy-csp-mixedreality.md#configuredevicestandbyaction)
- [ConfigureDeviceStandbyActionTimeout](policy-csp-mixedreality.md#configuredevicestandbyactiontimeout)

## NewsAndInterests

- [DisableWidgetsOnLockScreen](policy-csp-newsandinterests.md#disablewidgetsonlockscreen)
- [DisableWidgetsBoard](policy-csp-newsandinterests.md#disablewidgetsboard)

## PassportForWork CSP

- [DisablePostLogonProvisioning](passportforwork-csp.md#devicetenantidpoliciesdisablepostlogonprovisioning)

## Power

- [EnableEnergySaver](policy-csp-power.md#enableenergysaver)

## Printers

- [ConfigureIppTlsCertificatePolicy](policy-csp-printers.md#configureipptlscertificatepolicy)

## RemoteDesktopServices

- [TS_SERVER_REMOTEAPP_USE_SHELLAPPRUNTIME](policy-csp-remotedesktopservices.md#ts_server_remoteapp_use_shellappruntime)

## RemoteRemediation CSP

- [EnableCloudRemediation](remoteremediation-csp.md#cloudremediationsettingsenablecloudremediation)
- [EnableAutoRemediation](remoteremediation-csp.md#cloudremediationsettingsautoremediationsettingsenableautoremediation)
- [SetTimeToReboot](remoteremediation-csp.md#cloudremediationsettingsautoremediationsettingssettimetoreboot)
- [SetRetryInterval](remoteremediation-csp.md#cloudremediationsettingsautoremediationsettingssetretryinterval)
- [NetworkSSID](remoteremediation-csp.md#cloudremediationsettingsnetworksettingsnetworkcredentialsnetworkssid)
- [NetworkPassword](remoteremediation-csp.md#cloudremediationsettingsnetworksettingsnetworkcredentialsnetworkpassword)
- [NetworkPasswordEncryptionType](remoteremediation-csp.md#cloudremediationsettingsnetworksettingsnetworkcredentialsnetworkpasswordencryptiontype)
- [NetworkPasswordEncryptionStore](remoteremediation-csp.md#cloudremediationsettingsnetworksettingsnetworkcredentialsnetworkpasswordencryptionstore)

## SettingsSync

- [EnableWindowsBackup](policy-csp-settingssync.md#enablewindowsbackup)

## Start

- [AlwaysShowNotificationIcon](policy-csp-start.md#alwaysshownotificationicon)
- [TurnOffAbbreviatedDateTimeFormat](policy-csp-start.md#turnoffabbreviateddatetimeformat)

## SurfaceHub CSP

- [ExchangeModernAuthEnabled](surfacehub-csp.md#deviceaccountexchangemodernauthenabled)

## System

- [DisableCHPE](policy-csp-system.md#disablechpe)

## TextInput

- [TouchKeyboardControllerModeAvailability](policy-csp-textinput.md#touchkeyboardcontrollermodeavailability)

## Update

- [AllowTemporaryEnterpriseFeatureControl](policy-csp-update.md#allowtemporaryenterprisefeaturecontrol)

## Wifi

- [AllowWFAQosManagementMSCS](policy-csp-wifi.md#allowwfaqosmanagementmscs)
- [AllowWFAQosManagementDSCPToUPMapping](policy-csp-wifi.md#allowwfaqosmanagementdscptoupmapping)

## WindowsAI

- [DisableAIDataAnalysis](policy-csp-windowsai.md#disableaidataanalysis)
- [SetDenyAppListForRecall](policy-csp-windowsai.md#setdenyapplistforrecall)
- [SetDenyUriListForRecall](policy-csp-windowsai.md#setdenyurilistforrecall)
- [SetMaximumStorageSpaceForRecallSnapshots](policy-csp-windowsai.md#setmaximumstoragespaceforrecallsnapshots)
- [SetMaximumStorageDurationForRecallSnapshots](policy-csp-windowsai.md#setmaximumstoragedurationforrecallsnapshots)
- [DisableClickToDo](policy-csp-windowsai.md#disableclicktodo)
- [DisableImageCreator](policy-csp-windowsai.md#disableimagecreator)
- [DisableCocreator](policy-csp-windowsai.md#disablecocreator)
- [DisableGenerativeFill](policy-csp-windowsai.md#disablegenerativefill)
- [AllowRecallEnablement](policy-csp-windowsai.md#allowrecallenablement)

## WindowsBackupAndRestore CSP

- [EnableWindowsRestore](windowsbackupandrestore-csp.md#enablewindowsrestore)

## WindowsLicensing CSP

- [SubscriptionType](windowslicensing-csp.md#subscriptionssubscriptiontype)
- [SubscriptionStatus](windowslicensing-csp.md#subscriptionssubscriptionstatus)
- [SubscriptionLastError](windowslicensing-csp.md#subscriptionssubscriptionlasterror)
- [SubscriptionLastErrorDescription](windowslicensing-csp.md#subscriptionssubscriptionlasterrordescription)
- [DisableSubscription](windowslicensing-csp.md#subscriptionsdisablesubscription)
- [RemoveSubscription](windowslicensing-csp.md#subscriptionsremovesubscription)

## WirelessNetworkPreference CSP

- [IsEnabled](wirelessnetworkpreference-csp.md#isenabled)
- [PreferCellularOverWiFi](wirelessnetworkpreference-csp.md#prefercellularoverwifi)
- [eSIMprofilesCount](wirelessnetworkpreference-csp.md#statusesimprofilescount)
- [eSIMprofilesMatched](wirelessnetworkpreference-csp.md#statusesimprofilesmatched)
- [eSIMpolicyStatus](wirelessnetworkpreference-csp.md#statusesimpolicystatus)
- [NetworkDiscoveryOption](wirelessnetworkpreference-csp.md#parameterscellularparametersnetworkdiscoveryoption)
- [MaxRescanIntervalInSeconds](wirelessnetworkpreference-csp.md#parameterscellularparametersmaxrescanintervalinseconds)
- [PreferredProfileWakeConnectionTimerInSeconds](wirelessnetworkpreference-csp.md#parameterscellularparameterspreferredprofilewakeconnectiontimerinseconds)
- [ProfileRegistrationTimerInSeconds](wirelessnetworkpreference-csp.md#parameterscellularparametersprofileregistrationtimerinseconds)
- [ScreenOffDurationToTriggerNetworkDiscoveryInMinutes](wirelessnetworkpreference-csp.md#parameterscellularparametersscreenoffdurationtotriggernetworkdiscoveryinminutes)
- [Priority](wirelessnetworkpreference-csp.md#connectionprofilesconnectionprofileidpriority)
- [WirelessType](wirelessnetworkpreference-csp.md#connectionprofilesconnectionprofileidwirelesstype)
- [PLMNID](wirelessnetworkpreference-csp.md#connectionprofilesconnectionprofileidcellularplmnid)

## Related articles

[Policy configuration service provider](policy-configuration-service-provider.md)
