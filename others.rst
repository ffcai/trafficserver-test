Others
******

Log
===

#. Configuration

   Rewrite with new_tsqa: `test-log-configuration <https://github.com/apache/trafficserver/blob/master/ci/tsqa/test-log-configuration>`_

#. Refcounting

   Rewrite with new_tsqa: `test-log-refcounting <https://github.com/apache/trafficserver/blob/master/ci/tsqa/test-log-refcounting>`_

#. Heartbeat

   ::

    proxy.config.http.record_heartbeat

   Set to ``1``: Test if Traffic Server enables ``traffic_cop``'s heartbeat logging.

Traffic Line
============

Rewrite with new_tsqa: `test-trafficline-metrics <https://github.com/apache/trafficserver/blob/master/ci/tsqa/test-trafficline-metrics>`_

Intercept Plugin
================

Set ``remap.config``: ::

    intercept.so

Done: `test_example <https://github.com/apache/trafficserver/blob/master/ci/new_tsqa/tests/test_example.py>`_
