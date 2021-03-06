---
label: UserProfileService
id: UserProfileService
categorySlug: 'core'
categoryLabel: 'core'
categorySort: 'alphabetical'
documentSort: 'alphabetical'

### Function

**$().SPServices**

### Web Service

**UserProfileService**

A big thanks to Matt Bramer for his help in wrapping the remaining operations for this Web Service.

### Supported Operations

| Operation | Options | MSDN Documentation | Introduced |
| --------- | ------- | ------------------ | ---------- |
| AddColleague | `accountName, colleagueAccountName, group, privacy, isInWorkGroup` | [UserProfileService.AddColleague Method](http://msdn.microsoft.com/en-us/library/aa981615(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| AddLink | `accountName, name, url, group, privacy` | [UserProfileService.AddLink Method](http://msdn.microsoft.com/en-us/library/websvcuserprofileservice.userprofileservice.addlink(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| AddMembership | `accountName, membershipInfo, group, privacy` | [UserProfileService.AddMembership Method](http://msdn.microsoft.com/en-us/library/aa981520(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| AddPinnedLink | `accountName, name, url` | [UserProfileService.AddPinnedLink Method](http://msdn.microsoft.com/en-us/library/aa981075(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| CreateMemberGroup | `membershipInfo` | [UserProfileService.CreateMemberGroup Method](http://msdn.microsoft.com/en-us/library/aa981363(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| CreateUserProfileByAccountName | `accountName` | [UserProfileService.CreateUserProfileByAccountName Method](http://msdn.microsoft.com/en-us/library/aa981026(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| GetCommonColleagues | `accountName` | [UserProfileService.GetCommonColleagues Method](http://msdn.microsoft.com/en-us/library/aa981308(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| GetCommonManager | `accountName` | [UserProfileService.GetCommonManager Method](http://msdn.microsoft.com/en-us/library/aa981607(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| GetCommonMemberships | `accountName` | [UserProfileService.GetCommonMemberships Method](http://msdn.microsoft.com/en-us/library/microsoft.office.server.userprofiles.userprofileservice.getcommonmemberships.aspx) | [0.3.0](http://spservices.codeplex.com/Release/ProjectReleases.aspx?ReleaseId=33030) |
| GetInCommon | `accountName` | [UserProfileService.GetInCommon Method](http://msdn.microsoft.com/en-us/library/aa981053(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| GetPropertyChoiceList | `propertyName` | [UserProfileService.GetPropertyChoiceList Method](http://msdn.microsoft.com/en-us/library/aa981557(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| GetUserColleagues | `accountName` | [UserProfileService.GetUserColleagues Method](http://msdn.microsoft.com/en-us/library/websvcuserprofileservice.userprofileservice.getusercolleagues(v=office.14).aspx) | [0.3.0](http://spservices.codeplex.com/Release/ProjectReleases.aspx?ReleaseId=33030) |
| GetUserLinks | `accountName` | [UserProfileService.GetUserLinks Method](http://msdn.microsoft.com/en-us/library/websvcuserprofileservice.userprofileservice.getuserlinks) | [0.3.0](http://spservices.codeplex.com/Release/ProjectReleases.aspx?ReleaseId=33030) |
| GetUserMemberships | `accountName` | [UserProfileService.GetUserMemberships Method](http://msdn.microsoft.com/en-us/library/microsoft.office.server.userprofiles.userprofileservice.getusermemberships.aspx) | [0.3.0](http://spservices.codeplex.com/Release/ProjectReleases.aspx?ReleaseId=33030) |
| GetUserPinnedLinks | `accountName` | [UserProfileService.GetUserPinnedLinks Method](http://msdn.microsoft.com/en-us/library/microsoft.office.server.userprofiles.userprofileservice.getuserpinnedlinks.aspx) | [0.3.0](http://spservices.codeplex.com/Release/ProjectReleases.aspx?ReleaseId=33030) |
| GetUserProfileByGuid | guid | [UserProfileService.GetUserProfileByGuid Method](http://msdn.microsoft.com/en-us/library/aa981445(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| GetUserProfileByIndex | index | [UserProfileService.GetUserProfileByIndex Method](http://msdn.microsoft.com/en-us/library/aa981288(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| [GetUserProfileByName](/docs/code/api/UserProfileService-GetUserProfileByName.md) | `AccountName` | [UserProfileService.GetUserProfileByName Method](http://msdn.microsoft.com/en-us/library/microsoft.office.server.userprofiles.userprofileservice.getuserprofilebyname.aspx) | [0.3.0](http://spservices.codeplex.com/Release/ProjectReleases.aspx?ReleaseId=33030) |
| GetUserProfileCount | _None_ | [UserProfileService.GetUserProfileCount Method](http://msdn.microsoft.com/en-us/library/microsoft.office.server.userprofiles.userprofileservice.getuserprofilecount.aspx) | [0.3.0](http://spservices.codeplex.com/Release/ProjectReleases.aspx?ReleaseId=33030) |
| GetUserProfileSchema | _None_ | [UserProfileService.GetUserProfileSchema Method](http://msdn.microsoft.com/en-us/library/microsoft.office.server.userprofiles.userprofileservice.getuserprofileschema.aspx) | [0.3.0](http://spservices.codeplex.com/Release/ProjectReleases.aspx?ReleaseId=33030) |
| [ModifyUserPropertyByAccountName](/docs/code/api/UserProfileService-ModifyUserPropertyByAccountName.md) | `accountName, newData` | [UserProfileService.ModifyUserPropertyByAccountName Method](http://msdn.microsoft.com/en-us/library/aa981350.aspx) | [0.5.0](http://spservices.codeplex.com/Release/ProjectReleases.aspx?ReleaseId=34865) |
| RemoveAllColleagues | `accountName` | [UserProfileService.RemoveAllColleagues Method](http://msdn.microsoft.com/en-us/library/aa980899(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| RemoveAllLinks | `accountName` | [UserProfileService.RemoveAllLinks Method](http://msdn.microsoft.com/en-us/library/aa981279(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| RemoveAllMemberships | `accountName` | [UserProfileService.RemoveAllMemberships Method](http://msdn.microsoft.com/en-us/library/aa981195(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| RemoveAllPinnedLinks | `accountName` | [UserProfileService.RemoveAllPinnedLinks Method](http://msdn.microsoft.com/en-us/library/aa981074(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| RemoveColleague | `accountName`, colleagueAccountName | [UserProfileService.RemoveColleague Method](http://msdn.microsoft.com/en-us/library/aa980880(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| RemoveLink | `accountName`, id | [UserProfileService.RemoveLink Method](http://msdn.microsoft.com/en-us/library/aa981178(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| RemoveMembership | `accountName`, sourceInternal, sourceReference | [UserProfileService.RemoveMembership Method](http://msdn.microsoft.com/en-us/library/aa981247(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| RemovePinnedLink | `accountName`, id | [UserProfileService.RemovePinnedLink Method](http://msdn.microsoft.com/en-us/library/aa981494(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| UpdateColleaguePrivacy | accountName, colleagueAccountName, newPrivacy | [UserProfileService.UpdateColleaguePrivacy Method](http://msdn.microsoft.com/en-us/library/aa981431(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| UpdateLink | `accountName`, data | [UserProfileService.UpdateLink Method](http://msdn.microsoft.com/en-us/library/aa981510(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| UpdateMembershipPrivacy | `accountName`, sourceInternal, sourceReference, newPrivacy | [UserProfileService.UpdateMembershipPrivacy Method](http://msdn.microsoft.com/en-us/library/aa981139(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |
| UpdatePinnedLink | `accountName`, data | [UserProfileService.UpdatePinnedLink Method](http://msdn.microsoft.com/en-us/library/aa980870(v=office.12).aspx) | [0.6.0](http://spservices.codeplex.com/releases/view/55660) |