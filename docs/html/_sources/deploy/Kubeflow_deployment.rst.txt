===================
Kubeflow deployment
===================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Kubeflow/kfserving based deployment
-----------------------------------

* Folder "/LSTM_kfserving_deploy/knative-app/kfserving-yaml/"

.. literalinclude:: ../../../LSTM_kfserving_deploy/knative-app/kfserving-yaml/har.yaml

* How to deploy

.. code-block::

   kubectl apply -f har.yaml

* Check Kubeflow inferenceservices status

.. code-block::

    kubectl get inferenceservices

Kubeflow/kfserving WebApp to interact with Kubeflow model
----------------------------------------------------------

* Folder "/LSTM_kfserving_deploy/knative-app/Docker-HarWebApp-for-Kfserving/"

.. literalinclude:: ../../../LSTM_kfserving_deploy/knative-app/Docker-HarWebApp-for-Kfserving/app.yaml

* How to deploy

.. code-block::

   kubectl apply -f app.yaml

* Check kubenetes svc status

.. code-block::

    kubectl get svc


Kubernetes application based deployment (no Kubeflow)
-----------------------------------------------------
This App will carry model by itself for demo purpose.

* Folder "/LSTM_kfserving_deploy/knative-app/Docker-HarWebApp/"

.. literalinclude:: ../../../LSTM_kfserving_deploy/knative-app/Docker-HarWebApp/service.yaml

* How to deploy

.. code-block::

   kubectl apply -f service.yaml

* Check Kubenetes pod and svc status

.. code-block::

    kubectl get svc

Kubenetes sendDataApp to send test data to App/Model
----------------------------------------------------
This App will send test data to WebApp for demo purpose.


* Folder "/LSTM_kfserving_deploy/knative-app/Docker-sendDataApp/"

.. literalinclude:: ../../../LSTM_kfserving_deploy/knative-app/Docker-sendDataApp/app.yaml

* How to deploy

.. code-block::

   kubectl apply -f app.yaml

* Check kubenetes deployment status

.. code-block::

    kubectl get deployments




