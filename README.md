"# Youtube" 


UI :-
	buttons(search, thumbnails, description, like, comment)

Frontend :-
	click on search, click on thumbnail to play video, upload video, working of like, comment, and subscribe buttons

Backend :-
	when user search a video, relevant all videos are showed to user based on keywords. That videos are taken from youtube server where all videos are stored.

Database(Youtube server) :-
	when a user upload a video, it first go to youtube server and saved.





Youtube Working(Request Methods)

GET :-
	When we search for some video, this is GET req. Youtube show us the video according to our req and these videos comes from youtube server.

POST :-
	When we upoad video on our channel this is POST req.

DELETE :-
	When we delete video from our channel this is DELETE req.

PUT :-
	Youtube does not support PUT req as if we upload the same video which we have updated earlier, it will take it as new video, does not matter our video is same as our first video or not.

PATCH :-
	Youtube does not support PATCH req also, we can't make changes to our video which we had uploaded.