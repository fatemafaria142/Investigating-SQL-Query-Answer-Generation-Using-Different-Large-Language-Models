<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SQL Query Answer Generation Research</title>
</head>
<body>

<h1>SQL Query Answer Generation Research</h1>

<p>
    <strong>Dataset:</strong> 
    <a href="https://huggingface.co/datasets/b-mc2/sql-create-context">sql-create-context</a>
    <br>
    <strong>Dataset Description:</strong> There are 78,577 examples of natural language queries, SQL CREATE TABLE statements, and SQL Query answering the question using the CREATE statement as context. This dataset was built with text-to-SQL LLMs in mind, intending to prevent hallucination of column and table names often seen when trained on text-to-SQL datasets. A subset of this dataset was used for the project.
</p>

<p>
    <strong>Models Used:</strong>
    <ul>
        <li><a href="https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1">Mistral-7B-Instruct-v0.1</a></li>
        <li><a href="https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2">Mistral-7B-Instruct-v0.2</a></li>
        <li><a href="https://huggingface.co/berkeley-nest/Starling-LM-7B-alpha">Starling-LM-7B-alpha</a></li>
        <li><a href="https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0">TinyLlama</a></li>
        <li><a href="https://huggingface.co/openchat/openchat-3.5-1210">OpenChat 3.5 1210</a></li>
    </ul>
</p>

<p>
    <strong>Model Descriptions:</strong>
    <ul>
        <li><strong>Mistral-7B-Instruct-v0.1:</strong> Instruct fine-tuned version of Mistral-7B-v0.1 generative text model using conversation datasets.</li>
        <li><strong>Mistral-7B-Instruct-v0.2:</strong> Improved instruct fine-tuned version of Mistral-7B-Instruct-v0.1.</li>
        <li><strong>Starling-LM-7B-alpha:</strong> Trained by Reinforcement Learning from AI Feedback (RLAIF) using OpenChat 3.5 with reward model Starling-RM-7B-alpha.</li>
        <li><strong>TinyLlama:</strong> Compact 1.1B Llama model pre-trained on 3 trillion tokens.</li>
        <li><strong>OpenChat 3.5 1210:</strong> OpenChat model.</li>
    </ul>
</p>

<p>
    <strong>Model Links:</strong>
    <ul>
        <li><a href="https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1">Mistral-7B-Instruct-v0.1 Model</a></li>
        <li><a href="https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2">Mistral-7B-Instruct-v0.2 Model</a></li>
        <li><a href="https://huggingface.co/berkeley-nest/Starling-LM-7B-alpha">Starling-LM-7B-alpha Model</a></li>
        <li><a href="https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0">TinyLlama Model</a></li>
        <li><a href="https://huggingface.co/openchat/openchat-3.5-1210">OpenChat 3.5 1210 Model</a></li>
    </ul>
</p>

</body>
</html>
