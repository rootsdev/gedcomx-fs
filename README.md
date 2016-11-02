Unoffical documentation of FamilySearch extensions to [GEDCOM X](http://www.gedcomx.org/).

The are no official docs but we have the canonical [Java implementation](https://github.com/FamilySearch/gedcomx-java/tree/master/extensions/familysearch/familysearch-api-model/src/main/java/org/familysearch/platform)
which is used to generate the [FamilySearch developer docs](https://familysearch.org/developers/docs/api/fs_json).
We use the Java code to obtain a list of extensions but link to the developer 
docs for consumable documentation.

## Data Types

* [ArtifactMetadata](https://familysearch.org/developers/docs/api/types/json_ArtifactMetadata) - I don't know where this is used
* [ChangeInfo](https://familysearch.org/developers/docs/api/types/json_ChangeInfo)
* [ChildAndParentsRelationship](https://familysearch.org/developers/docs/api/types/json_ChildAndParentsRelationship)
* [Comment](https://familysearch.org/developers/docs/api/types/json_Comment)
* [Discussion](https://familysearch.org/developers/docs/api/types/json_Discussion)
* [DiscussionReference](https://familysearch.org/developers/docs/api/types/json_DiscussionReference)
* [Error](https://familysearch.org/developers/docs/api/types/json_Error)
* [Feature](https://familysearch.org/developers/docs/api/types/json_Feature)
* [FeedbackInfo](https://familysearch.org/developers/docs/api/types/json_FeedbackInfo)
* [MatchInfo](https://familysearch.org/developers/docs/api/types/json_MatchInfo)
* [Merge](https://familysearch.org/developers/docs/api/types/json_Merge)
* [MergeAnalysis](https://familysearch.org/developers/docs/api/types/json_MergeAnalysis)
* [MergeConflict](https://familysearch.org/developers/docs/api/types/json_MergeConflict)
* [Ordinance](https://familysearch.org/developers/docs/api/types/json_Ordinance)
* [Reservation](https://familysearch.org/developers/docs/api/types/json_Reservation)
* [SearchInfo](https://familysearch.org/developers/docs/api/types/json_SearchInfo)
* [Tag](https://familysearch.org/developers/docs/api/types/json_Tag)
* [User](https://familysearch.org/developers/docs/api/types/json_User)
* [UserHistoryInfo](https://familysearch.org/developers/docs/api/types/json_UserHistoryInfo) (Doesn't appear to be used)

## Property Extensions

* [Gedcomx](https://familysearch.org/developers/docs/api/types/json_FamilySearchPlatform) - Referred to in the docs as FamilySearch, a class which extends GedcomX.
  * childAndParentsRelationships
  * discussions
  * users
  * merges
  * mergeAnalyses
  * features
  * feedbackInfo (not documented)
* AtomEntry.changeInfo
* AtomEntry.matchInfo
* AtomFeed.searchInfo
* SourceReference.tags
* Person.discussion-references

## Enumerations

* [artifactScreeningState](https://familysearch.org/developers/docs/api/types/xml_fs_artifactScreeningState)
* [changeObjectModifier](https://familysearch.org/developers/docs/api/types/xml_fs_changeObjectModifier)
* [changeObjectType](https://familysearch.org/developers/docs/api/types/xml_fs_changeObjectType)
* [changeOperation](https://familysearch.org/developers/docs/api/types/xml_fs_changeOperation)
* [matchStatus](https://familysearch.org/developers/docs/api/types/xml_fs_matchStatus)
* [ordinanceStatus](https://familysearch.org/developers/docs/api/types/xml_fs_ordinanceStatus)
