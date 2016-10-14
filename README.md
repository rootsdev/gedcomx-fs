Unoffical documentation of FamilySearch extensions to [GEDCOM X](http://www.gedcomx.org/).

The are no official docs but we have the canonical [Java implementation](https://github.com/FamilySearch/gedcomx-java/tree/master/extensions/familysearch/familysearch-api-model/src/main/java/org/familysearch/platform)
which is used to generate the [FamilySearch developer docs](https://familysearch.org/developers/docs/api/fs_json).
We use the Java code to obtain a list of extensions but link to the developer 
docs for consumable documentation.

## Data Types

* [ArtifactMetadata](https://familysearch.org/developers/docs/api/fs/ArtifactMetadata_json)
* [ChangeInfo](https://familysearch.org/developers/docs/api/fs/ChangeInfo_json)
* [ChildAndParentsRelationship](https://familysearch.org/developers/docs/api/fs/ChildAndParentsRelationship_json)
* [Comment](https://familysearch.org/developers/docs/api/fs/Comment_json)
* [Discussion](https://familysearch.org/developers/docs/api/fs/Discussion_json)
* [DiscussionReference](https://familysearch.org/developers/docs/api/fs/DiscussionReference_json)
* [Error](https://familysearch.org/developers/docs/api/fs/Error_json)
* [FeatureSet](https://familysearch.org/developers/docs/api/fs/FeatureSet_json)
* [FeedbackInfo](https://familysearch.org/developers/docs/api/fs/FeedbackInfo_json)
* [MatchInfo](https://familysearch.org/developers/docs/api/fs/MatchInfo_json)
* [Merge](https://familysearch.org/developers/docs/api/fs/Merge_json)
* [MergeAnalysis](https://familysearch.org/developers/docs/api/fs/MergeAnalysis_json)
* [MergeConflict](https://familysearch.org/developers/docs/api/fs/MergeConflict_json)
* [Ordinance](https://familysearch.org/developers/docs/api/fs/Ordinance_json)
* [Reservation](https://familysearch.org/developers/docs/api/fs/Reservation_json)
* [SearchInfo](https://familysearch.org/developers/docs/api/fs/SearchInfo_json)
* [Tag](https://familysearch.org/developers/docs/api/fs/Tag_json)
* [User](https://familysearch.org/developers/docs/api/fs/User_json)
* [UserHistoryInfo](https://familysearch.org/developers/docs/api/fs/UserHistoryInfo_json) (Doesn't appear to be used)

## Property Extensions

* [Gedcomx](https://familysearch.org/developers/docs/api/fs/FamilySearch_json) - Referred to in the docs as FamilySearch, a class which extends GedcomX.
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

* [changeObjectModifier](https://familysearch.org/developers/docs/api/fs/changeObjectModifier_json)
* [changeObjectType](https://familysearch.org/developers/docs/api/fs/changeObjectType_json)
* [changeOperation](https://familysearch.org/developers/docs/api/fs/changeOperation_json)
* [matchStatus](https://familysearch.org/developers/docs/api/fs/matchStatus_json)
* [ordinanceStatus](https://familysearch.org/developers/docs/api/fs/ordinanceStatus_json)
