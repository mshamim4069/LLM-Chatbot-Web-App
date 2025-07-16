# LLM-Chatbot-Web-App
A full-stack AI chatbot powered by OpenAI's GPT-4, deployed on DigitalOcean Kubernetes, scalable via HPA, CI/CD via GitHub Actions, and served via a React frontend
llm-chatbot-app/
├── backend/
│   ├── main.py            # FastAPI app with /chat endpoint
│   ├── requirements.txt
│   └── Dockerfile
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   └── App.jsx
│   └── package.json
├── k8s/
│   ├── deployment.yaml
│   ├── service.yaml
│   ├── secret.yaml
│   └── hpa.yaml
├── .github/
│   └── workflows/
│       └── deploy.yml
├── terraform/
│   ├── main.tf
│   ├── variables.tf
│   └── outputs.tf
├── README.md
└── architecture.png   👈 (today’s goal)
