# JISC Learning Analytics Vocabulary
The following terms are in use in the Jisc learning analytics recipes.
NOTE: The xapi.jisc.ac.uk namespace URI may change.

### Verb

Usage:

- [verb.id](https://github.com/adlnet/xAPI-Spec/blob/master/xAPI.md#verb) -Corresponds to a Verb definition.

| Label  	   | Description | IRI  | Recipe Example 
| -------------| ----------- |------|----|
|  Logged in  | Logged in to some service  | [https://brindlewaye.com/xAPITerms/verbs/loggedin](https://brindlewaye.com/xAPITerms/verbs/loggedin)|[Logged in](recipes/login.md#verb) |
|  Logged out | Logged out of some service  | [https://brindlewaye.com/xAPITerms/verbs/loggedout](https://brindlewaye.com/xAPITerms/verbs/loggedout")|[Logged out](recipes/logout.md#verb) |
|  Viewed     | Indicates that the actor has viewed the object  |	[http://id.tincanapi.com/verb/viewed](http://id.tincanapi.com/verb/viewed) | [Object Viewed](recipes/Module-View.md#verb) |


### Object


Usage:

objects for:
- [object.definition.type](https://github.com/adlnet/xAPI-Spec/blob/master/xAPI.md#activity-definition) -The type of Activity.

| Label  		| Description   | IRI    | Recipe example
| ------------- | ------------- |--------|----------------|
| Application   | Represents any kind of software application   | [ http://activitystrea.ms/schema/1.0/application](http://activitystrea.ms/schema/1.0/application)  	|[Logged in](recipes/login.md#complete_example) |


Usage:

atomic values for:

| VLE forum  	| A VLE forum/discussion board   | http://xapi.jisc.ac.uk/vle/forum |                                              |[A forum](http://moodle.data.alpha.jisc.ac.uk/mod/forum/view.php?id=12)| [Discussion board](https://jisc.blackboard.com/webapps/discussionboard/do/forum?action=list_threads&course_id=_144_1&forum_id=81&nav=discussion_board&conf_id=_164_1&content_id=_218_1&mode=view)  |
| External URL  | An external URL                | http://xapi.jisc.ac.uk/externalURL | | | 
| File   | Accessing any kind of non-web native file type. e.g. MS office, video or audio.           | http://xapi.jisc.ac.uk/vle/file | | | 



### Context

Usage:
- [Context.extensions](https://github.com/adlnet/xAPI-Spec/blob/master/xAPI.md#416-context)

| Label  		| Description   | IRI    | Recipe example
| ------------- | ------------- |------------------------------------------------------|----|
| Umbrella course area |  Umbrella course/parent area by its home page URI         | http://xapi.jisc.ac.uk/courseArea | |
| Session id 	|  local session id       | http://xapi.jisc.ac.uk/sessionId | |
| IP address	|  client's address location on internet     | http://id.tincanapi.com/extension/ip-address | |
| Recipe Version|  Version of Recipe used. Version number can be found on recipe page    | http://xapi.jisc.ac.uk/recipeVersion | |

