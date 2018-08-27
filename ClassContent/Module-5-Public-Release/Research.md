# Research

## Topics

1. Last Thoughts on Deployment

---

# Last Thoughts on Deployment

## [A Case for Manual Database Migrations to Production](https://blog.staffjoy.com/dont-migrate-databases-automatically-5039ab061365) (3m read)
With automation being the key for reducing the number of manual touch points that create opportunities for human error,  database migrations are the exception that proves the rule. This short article demonstrates why exactly automating migrations can be problematic and one company's solution on how to move past that issue.

## [Race Conditions on Database Deployments](http://www.brunton-spall.co.uk/post/2014/05/06/database-migrations-done-right/) (10m read)
Very much inline with the other article on a case for manual database migrations but from a more technical point of view.

## [A Case Against ORMs](http://woz.posthaven.com/what-orms-have-taught-me-just-learn-sql) (20m read)
Development can be quite opinionated and I want to present you with another point of view with regards to how to handle data in a Continuous Delivery environment… write your own solution. At the end of the day, every ORM is dynamically handling the heavy lifting for you. If you have the time, the patients, and the need, you can write your own solution from scratch. This article explores the rationale behind just learning SQL, and using it to write your own ORM alternative.