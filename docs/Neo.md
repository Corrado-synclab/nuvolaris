<!--
  ~ Licensed to the Apache Software Foundation (ASF) under one
  ~ or more contributor license agreements.  See the NOTICE file
  ~ distributed with this work for additional information
  ~ regarding copyright ownership.  The ASF licenses this file
  ~ to you under the Apache License, Version 2.0 (the
  ~ "License"); you may not use this file except in compliance
  ~ with the License.  You may obtain a copy of the License at
  ~
  ~   http://www.apache.org/licenses/LICENSE-2.0
  ~
  ~ Unless required by applicable law or agreed to in writing,
  ~ software distributed under the License is distributed on an
  ~ "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
  ~ KIND, either express or implied.  See the License for the
  ~ specific language governing permissions and limitations
  ~ under the License.
  ~
-->
# Neo milestone

This is our first milestone. We want to release just an operator that runs OpenWhisk standalone (no Kafka, Couchdb and other components yet).

We start building:

- an image with the standalone OpenWhisk  controller #5
- a operator that launches such a controller #3
- a set of runtimes to be used by such an image #4
- a test suite to test it at least in Docker Desktop and in one Kubernetes cluster built with Microk8s #2

