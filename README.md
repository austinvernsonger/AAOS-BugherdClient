# AAOS-BugherdClient
Rest Client for the BugHerd API



-------

**AAOS Bugherd URL EndPoint:** [https://www.bugherd.com/api_v2/projects/73659/](https://www.bugherd.com/api_v2/projects/73659/)

**API TOKEN:** Private

-------

### Below is an explanation of the output:

`id: globally unique ID`

`local_task_id: ID within the project`

`project_id: ID of the containing project`

`created_at: timestamp in the form YYYY-MM-DDThh:mm:ssZ`

`updated_at: timestamp in the form YYYY-MM-DDThh:mm:ssZ`

`closed_at: timestamp in the form YYYY-MM-DDThh:mm:ssZ or null`

`deleted_at: timestamp in the form YYYY-MM-DDThh:mm:ssZ or null`

`description: the user-entered text to describe the problem`

`status: backlog, todo, doing, done or closed`

`status_id: integer for status or null, 0 = backlog, 1 = todo, 2 = doing, 4 = done, 5 = closed`

`priority: not set, critical, important, normal or minor`

`priority_id: integer for severity 0 = N/A, 1 = critical, 2 = important, 3 = normal, 4 = minor`

`site: website this task was logged on`

`url: location of web page`

`tag_names: list of tags`

`external_id: value as set from api`

`requester_email: email address of the requester, if present`

`attachments: list of urls to the bug attachments`

`screenshot_url: url to the screenshot image for the bug`

`secret_link: unguessable url to the bug (does not require login)`

`admin_link: link to the bug in the task board (does require login)`

`assigned_to: user information on assignee`

`requester: user information on requester`
