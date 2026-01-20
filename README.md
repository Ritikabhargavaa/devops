<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Kubernetes Project README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #f9f9f9;
            color: #333;
        }
        h1, h2, h3 {
            color: #0b5ed7;
        }
        code {
            background-color: #eee;
            padding: 4px 6px;
            border-radius: 4px;
        }
        pre {
            background-color: #222;
            color: #f1f1f1;
            padding: 15px;
            border-radius: 6px;
            overflow-x: auto;
        }
        ul {
            line-height: 1.8;
        }
        .box {
            background: #ffffff;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            box-shadow: 0 0 8px rgba(0,0,0,0.05);
        }
    </style>
</head>
<body>

<h1>☸️ Kubernetes DevOps Project</h1>
<p>This project demonstrates a real-time DevOps workflow using <strong>Docker</strong> and <strong>Kubernetes</strong>.</p>

<div class="box">
<h2>📌 Project Overview</h2>
<p>
In this project, a containerized web application is deployed on a Kubernetes cluster using
Deployment and Service objects.
</p>
</div>

<div class="box">
<h2>🛠️ Technologies Used</h2>
<ul>
    <li>Docker</li>
    <li>Kubernetes (K8s)</li>
    <li>kubectl</li>
    <li>YAML</li>
    <li>Nginx</li>
</ul>
</div>

<div class="box">
<h2>📂 Project Structure</h2>
<pre>
k8s-project/
│── deployment.yml
│── service.yml
│── configmap.yml
│── secret.yml
│── README.html
</pre>
</div>

<div class="box">
<h2>🚀 How to Deploy</h2>
<pre>
kubectl apply -f deployment.yml
kubectl apply -f service.yml
</pre>
</div>

<div class="box">
<h2>🔍 Verify Deployment</h2>
<pre>
kubectl get pods
kubectl get services
</pre>
</div>

<div class="box">
<h2>📈 Scaling the Application</h2>
<pre>
kubectl scale deployment nginx-deployment --replicas=3
</pre>
</div>

<div class="box">
<h2>🧪 Troubleshooting</h2>
<ul>
    <li>Check pod logs: <code>kubectl logs &lt;pod-name&gt;</code></li>
    <li>Describe pod: <code>kubectl describe pod &lt;pod-name&gt;</code></li>
    <li>Check events: <code>kubectl get events</code></li>
</ul>
</div>

<div class="box">
<h2>🧹 Cleanup</h2>
<pre>
kubectl delete -f deployment.yml
kubectl delete -f service.yml
</pre>
</div>

<div class="box">
<h2>📚 Learning Outcomes</h2>
<ul>
    <li>Understanding Kubernetes architecture</li>
    <li>Hands-on with Deployment and Services</li>
    <li>Scaling and troubleshooting applications</li>
</ul>
</div>

<hr>

<p><strong>Author:</strong> Your Name</p>
<p><strong>Role:</strong> DevOps Engineer</p>

</body>
</html>
