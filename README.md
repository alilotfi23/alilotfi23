# 👨‍💻 DevOps & Cloud Engineer

🚀 Passionate about Cloud Computing, DevOps, and Automation.  
💡 Love working with Kubernetes, Terraform, and CI/CD pipelines.  
📚 Always learning new technologies to optimize infrastructure.  

## 🛠️ Tech Stack
```go
package main

import "fmt"

type Technology struct {
	BackEnd       map[string][]string
	DevOps        []string
	CloudServices map[string][]string
	Databases     []string
	Monitoring    []string
}

type Architecture struct {
	BackEnd   []string
	DevOps    []string
	Databases []string
	Networking []string
}

type Profile struct {
	Code         []string
	AskMeAbout   []string
	Technologies Technology
	Architecture Architecture
}

func main() {
	me := Profile{
		Code:       []string{"Go", "Python", "Bash",},
		AskMeAbout: []string{"Cloud Computing", "DevOps", "Infrastructure as Code"},
		Technologies: Technology{
			BackEnd: map[string][]string{
				"Golang": {"Gin", "Echo"},
				"Python": {"Flask", "FastAPI"},
			},
			DevOps: []string{
				"Docker🐳", "Kubernetes", "Terraform", "Ansible", "Helm",
				"CI/CD", "GitHub Actions", "Jenkins", "ArgoCD",
			},
			CloudServices: map[string][]string{
				"AWS":        {"EC2", "S3", "Lambda", "CloudWatch", "RDS", "EKS", "Fargate"},
				"Azure":      {"Azure DevOps", "AKS", "Blob Storage", "Functions"},
				"GoogleCloud": {"GKE", "Cloud Run", "Cloud Storage"},
			},
			Databases:  []string{"PostgreSQL", "MongoDB", "SQLite", "Redis"},
			Monitoring: []string{"Prometheus", "Grafana", "Kibana", "Splunk"},
		},
		Architecture: Architecture{
			BackEnd:   []string{"Microservices", "Monolithic", "Serverless"},
			DevOps:    []string{"CloudFormation", "Pulumi", "Serverless Framework"},
			Databases: []string{"Relational", "NoSQL", "In-memory"},
			Networking: []string{"Istio", "Cilium", "OpenVPN", "Nginx"},
		},
	}

	fmt.Printf("%+v\n", me)
}
```
<img src="https://raw.githubusercontent.com/alilotfi23/alilotfi23/output/snake.svg" alt="Snake animation" />

###
