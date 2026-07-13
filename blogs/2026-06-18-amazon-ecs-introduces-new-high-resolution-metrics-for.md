---
title: "Amazon ECS introduces new high-resolution metrics for faster service auto scaling"
url: "https://aws.amazon.com/blogs/aws/amazon-ecs-introduces-new-high-resolution-metrics-for-faster-service-auto-scaling/"
date: "2026-06-18"
author: "Channy Yun (윤석찬)"
feed_url: "https://aws.amazon.com/blogs/aws/feed/"
---
Amazon Elastic Container Service (Amazon ECS) service auto scaling automatically adjusts task counts to meet workload demand with comprehensive scaling policies, including predictive scaling for recurring traffic patterns, scheduled scaling for planned events, and target tracking to scale dynamically on real-time metrics. You can choose proactive scaling by using predictive scaling (automatic) and scheduled scaling (customer-defined), or reactive scaling by using target tracking with just a target to scale on. Amazon ECS service auto scaling adjusts the number of tasks in an ECS service based on Amazon CloudWatch metrics, such as average CPU/Memory usage, request count per target, a custom metric such as queue depth, or demand surges by using advanced machine learning (ML) algorithms.
