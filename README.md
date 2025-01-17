# nd064_C1
Set up your environment to extend a Python Flask application:

![screenshot course-preparations](https://user-images.githubusercontent.com/90947936/149462081-9be2b867-97f6-4ce9-b3bc-df7a60d2995f.png)

Once all the pre-requisites are completed, you can get started on developing endpoints to describe the application state.

course-repository : { https://github.com/udacity/nd064_course_1 }

main-course: { https://classroom.udacity.com/courses/ud064/lessons/a75dca92-92d7-4301-b250-53dd5320e7a8/concepts/e87aa5a7-52da-4a84-8196-8b5a923dba7e }

1. ## Exercise 1 : endpoints for app status  
Extend the Python Flask application with /status and /metrics endpoints, considering the following requirements:
- Both endpoints should return an `HTTP 200` status code
- Both endpoints should return a `JSON response` e.g. {"user": "admin"}. (Note: the JSON response can be hardcoded at this stage)
- The `/status` endpoint should return a response similar to this example: result: OK - healthy
- The `/metrics` endpoint should return a response similar to this example: data: {UserCount: 140, UserCountActive: 23}

Tips: If you get stuck, feel free to check the solution video where detailed operations are demonstrated.

video https://www.youtube.com/watch?v=Kj_hGnViybg 

2. ## exercise 2 :: Application Logging 
Logging is a core factor in increasing the visibility and transparency of an application. When in troubleshooting or debugging scenarios, it is paramount to pin-point the functionality that impacted the service. This exercise will focus on bringing the logging capabilities to an application.

At this stage, you have extended the Hello World application to handle different endpoints. Once an endpoint is reached, a log line should be recorded showcasing this operation.

In this exercise, you need to further develop the Hello World application collect logs, with the following requirements:

- A log line should be recorded the timestamp and the requested endpoint e.g. ``"{{TIMESTAMP}}, {{ ENDPOINT_NAME}} endpoint was reached"``
- The logs should be stored in a file with the name ``app.log``. Refer to the [logging Python module for more details](https://docs.python.org/3/library/logging.html#logging.basicConfig).
- Enable the collection of Python logs at the ``DEBUG`` level. Refer to the logging Python module for more details.

Note: For the environment setup, follow the instructions in the previous exercise.

Tips: If you get stuck, feel free to check the solution video where detailed operations are demonstrated.

video https://www.youtube.com/watch?v=rdoXsSx1ghk 

3. ## conclusion ::: takeaway 

video [00:39]  [ND064 C1 L1 07 Lesson Conclusion](https://www.youtube.com/watch?v=kNkwSTksAUg) 
