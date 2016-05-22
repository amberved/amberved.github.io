---
layout: post
title:  "My encounter with Java Spark"
date:   2016-02-22 01:37:00 -0700
categories: Java Microservice framework Sparkjava
---

import static spark.Spark.*;

public class HelloWorld {
    public static void main(String[] args) {
        get("/hello", (req, res) -> "Hello World");
    }
}

Also 
Check out the Sparkjava @ [Sparkjava]

[Sparkjava]: http://sparkjava.com
