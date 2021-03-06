---
label: SocialDataService
id: SocialDataService
categorySlug: 'core'
categoryLabel: 'core'
categorySort: 'alphabetical'
documentSort: 'alphabetical'

### Function

**$().SPServices**

### Web Service

**SocialDataService**

### Supported Operations

| Operation | Options | MSDN Documentation | Introduced |
| --------- | ------- | ------------------ | ---------- |
| AddComment | `url, comment, [isHighPriority], title` | [SocialDataService.AddComment Method](http://msdn.microsoft.com/en-us/library/ff770898.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| AddTag | `url, termID, title, [isPrivate]` | [SocialDataService.AddTag Method](http://msdn.microsoft.com/en-us/library/ff770863.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| AddTagByKeyword | `url, keyword, title, [isPrivate]` | [SocialDataService.AddTagByKeyword Method](http://msdn.microsoft.com/en-us/library/ff770848.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| CountCommentsOfUser | `userAccountName` | [SocialDataService.CountCommentsOfUser Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.countcommentsofuser.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| CountCommentsOfUserOnUrl | `userAccountName, url` | [SocialDataService.CountCommentsOfUserOnUrl Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.countcommentsofuseronurl.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| CountCommentsOnUrl | `url` | [SocialDataService.CountCommentsOnUrl Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.countcommentsonurl.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| CountRatingsOnUrl | `url` | [SocialDataService.CountRatingsOnUrl Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.countratingsonurl.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| CountTagsOfUser | `userAccountName` | [SocialDataService.CountTagsOfUser Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.counttagsofuser.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| DeleteComment | `url, lastModifiedTime` | [SocialDataService.DeleteComment Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.deletecomment.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| DeleteRating | `url` | [SocialDataService.DeleteRating Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.deleterating.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| DeleteTag | `url, termID` | [SocialDataService.DeleteTag Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.deletetag.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| DeleteTagByKeyword | `url, keyword` | [SocialDataService.DeleteTagByKeyword Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.deletetagbykeyword.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| DeleteTags | `url` | [SocialDataService.DeleteTags Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.deletetags.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetAllTagTerms | `[maximumItemsToReturn]` | [SocialDataService.GetAllTagTerms Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.getalltagterms.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetAllTagTermsForUrlFolder | `urlFolder, maximumItemsToReturn` | [SocialDataService.GetAllTagTermsForUrlFolder Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.getalltagtermsforurlfolder.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetAllTagUrls | `termID` | [SocialDataService.GetAllTagUrls Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.getalltagurls.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetAllTagUrlsByKeyword | `keyword` | [SocialDataService.GetAllTagUrlsByKeywords Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.getalltagurlsbykeyword.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetCommentsOfUser | `userAccountName, [maximumItemsToReturn], [startIndex]` | [SocialDataService.GetCommentsOfUser Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.getcommentsofuser.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetCommentsOfUserOnUrl | `userAccountName, url` | [SocialDataService.GetCommentsOfUserOnUrl Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.getcommentsofuseronurl.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetCommentsOnUrl | `url, [maximumItemsToReturn], [startIndex], [excludeItemsTime]` | [SocialDataService.GetCommentsOnUrl Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.getcommentsonurl.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetRatingAverageOnUrl | `url` | [SocialDataService.GetRatingAverageOnUrl Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.getratingaverageonurl.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetRatingOfUserOnUrl | `userAccountName, url` | [SocialDataService.GetRatingOfUserOnUrl Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.getratingofuseronurl.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetRatingOnUrl | `url` | [SocialDataService.GetRatingOnUrl Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.getratingonurl.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetRatingsOfUser | `userAccountName` | [SocialDataService.GetRatingsOfUser Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.getratingsofuser.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetRatingsOnUrl | `url` | [SocialDataService.GetRatingsOnUrl Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.getratingsonurl.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetSocialDataForFullReplication | `userAccountName` | [SocialDataService.GetSocialDataForFullReplication Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.getsocialdataforfullreplication.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetTags | `url` | [SocialDataService.GetTags Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.gettags.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetTagsOfUser | `userAccountName, [maximumItemsToReturn], [startIndex]` | [SocialDataService.GetTagsOfUser Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.gettagsofuser.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetTagTerms | `[maximumItemsToReturn]` | [SocialDataService.GetTagTerms Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.gettagterms.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetTagTermsOfUser | `userAccountName, [maximumItemsToReturn]` | [SocialDataService.GetTagTermsOfUser Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.gettagtermsofuser.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetTagTermsOnUrl | `url, [maximumItemsToReturn]` | [SocialDataService.GetTagTermsOnUrl Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.gettagtermsonurl.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetTagUrls | `termID` | [SocialDataService.GetTagUrls Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.gettagurls.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetTagUrlsByKeyword | `keyword` | [SocialDataService.GetTagUrlsByKeyword Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.gettagurlsbykeyword.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetTagUrlsOfUser | `termID, `userAccountName`` | [SocialDataService.GetTagUrlsOfUser Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.gettagurlsofuser.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| GetTagUrlsOfUserByKeyword | `keyword, `userAccountName`` | [SocialDataService.GetTagUrlsOfUserByKeyword Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.gettagurlsofuserbykeyword.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| SetRating | `url, rating, title, analysisDataEntry*` | [SocialDataService.SetRating Method](http://msdn.microsoft.com/en-us/library/ff770884.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |
| UpdateComment | `url, lastModifiedTime, comment, isHighPriority` | [SocialDataService.UpdateComment Method](http://msdn.microsoft.com/en-us/library/websvcsocialdataservice.socialdataservice.updatecomment.aspx) | [0.5.8](http://spservices.codeplex.com/releases/view/53275) |

* The documentation claims that analysisDataEntry is required, but in my testing it is not. There also don’t seem to be any user settable values in the XML structure.