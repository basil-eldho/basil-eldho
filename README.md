<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:001a00,100:00ff41&height=130&section=header&text=Basil%20Eldho&fontSize=50&fontColor=00ff41&animation=fadeIn&fontAlignY=65" width="100%"/>
</div>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00FF41&center=true&vCenter=true&width=700&lines=cat+%2Fproc%2Fself%2Fstatus+%7C+grep+Name;Go+%7C+eBPF+%7C+Systems+Engineer;uprobes+on+runtime.schedule+%E2%80%94+gowaite;KubeVirt+Contributor+%7C+SUNY+Binghamton+MS+CS;OPT+available+Jan+2027" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=basil-eldho&label=Profile+Views&color=00ff41&style=flat" />
  <a href="https://linkedin.com/in/basil-eldho"><img src="https://img.shields.io/badge/-LinkedIn-0d1117?style=flat&logo=linkedin&logoColor=00ff41"/></a>
  <a href="https://latencylog.tech"><img src="https://img.shields.io/badge/-latencylog.tech-0d1117?style=flat&logo=hashnode&logoColor=00ff41"/></a>
  <a href="mailto:basileljol@gmail.com"><img src="https://img.shields.io/badge/-Email-0d1117?style=flat&logo=gmail&logoColor=00ff41"/></a>
</p>

---

### `$ whoami`

🧠 &nbsp;Deep interest in **OS internals, networking, distributed systems, and performance engineering**\
🔬 &nbsp;Built **gowaite** — eBPF uprobes on `runtime.schedule`, `gcSTW`, `park`, `goready`\
💼 &nbsp;3+ yrs production Go at **Altro** (YC-backed fintech) & **Privcy AI** (London)\
📝 &nbsp;Writing about internals at **[latencylog.tech](https://latencylog.tech)**\
🎓 &nbsp;MS CS @ SUNY Binghamton (GPA 3.7, Dec 2026)\
📍 &nbsp;Binghamton, NY · OPT Jan 2027 · H-1B sponsorship required

### `$ cat ~/interests`

```
- Operating Systems    → schedulers, memory management, virtual memory, syscalls
- Networking           → transport layer, congestion control, protocol internals, RDMA
- Distributed Systems  → consensus, replication, consistency, fault tolerance
- Performance          → profiling, low-latency I/O, cache efficiency, eBPF tracing
- Adjacent             → compilers, hardware/ISA design, HFT systems, observability
```

---

```go
package main

import "fmt"

type Engineer struct {
	Name   string
	Stack  []string
	Reads  []string
	Status string
}

func main() {
	me := Engineer{
		Name:  "Basil Eldho",
		Stack: []string{"Go", "eBPF", "C", "Kubernetes", "Linux"},
		Reads: []string{
			"OSTEP",       // Operating Systems: Three Easy Pieces
			"CS:APP",      // Bryant & O'Hallaron
			"Kurose&Ross", // Computer Networking
		},
		Status: "OPT Jan 2027 · open to offers",
	}
	fmt.Printf("$ echo 'Hi, I am %s'\n", me.Name)
}
```

---

### `$ cat /proc/currently-reading`

| Book | Why |
|---|---|
| **OSTEP** — Operating Systems: Three Easy Pieces | Processes, virtual memory, concurrency from first principles |
| **CS:APP** — Bryant & O'Hallaron | Memory hierarchy, linking, systems programming |
| **Kurose & Ross** — Computer Networking | Transport layer, congestion control, protocol internals |
| **Princeton Computer Architecture** (YouTube) | Pipelining, caches, ISA design |

---

### `$ lscpu` &nbsp;Tech Stack

**Languages**\
![Go](https://img.shields.io/badge/-Go-0d1117?style=flat&logo=go&logoColor=00ADD8)&nbsp;
![C](https://img.shields.io/badge/-C-0d1117?style=flat&logo=c&logoColor=A8B9CC)&nbsp;
![C++](https://img.shields.io/badge/-C++-0d1117?style=flat&logo=c%2B%2B&logoColor=00599C)&nbsp;
![Python](https://img.shields.io/badge/-Python-0d1117?style=flat&logo=python&logoColor=3776AB)

**Kernel & Systems**\
![eBPF](https://img.shields.io/badge/-eBPF-0d1117?style=flat&logo=linux&logoColor=00ff41)&nbsp;
![Linux](https://img.shields.io/badge/-Linux-0d1117?style=flat&logo=linux&logoColor=FCC624)&nbsp;
![epoll](https://img.shields.io/badge/-epoll%20%2F%20non--blocking%20I%2FO-0d1117?style=flat&logo=linux&logoColor=A8B9CC)&nbsp;
![Go GMP](https://img.shields.io/badge/-Go%20GMP%20Scheduler-0d1117?style=flat&logo=go&logoColor=00ADD8)

**Observability**\
![Prometheus](https://img.shields.io/badge/-Prometheus-0d1117?style=flat&logo=prometheus&logoColor=E6522C)&nbsp;
![OpenTelemetry](https://img.shields.io/badge/-OpenTelemetry-0d1117?style=flat&logo=opentelemetry&logoColor=white)&nbsp;
![SigNoz](https://img.shields.io/badge/-SigNoz-0d1117?style=flat&logo=grafana&logoColor=F46800)

**Infrastructure**\
![Kubernetes](https://img.shields.io/badge/-Kubernetes-0d1117?style=flat&logo=kubernetes&logoColor=326CE5)&nbsp;
![Docker](https://img.shields.io/badge/-Docker-0d1117?style=flat&logo=docker&logoColor=2496ED)&nbsp;
![AWS](https://img.shields.io/badge/-AWS-0d1117?style=flat&logo=amazonaws&logoColor=FF9900)&nbsp;
![Git](https://img.shields.io/badge/-Git-0d1117?style=flat&logo=git&logoColor=F05032)

---

### `$ ls -la ~/projects`

**Systems & Observability**

[![gowaite](https://img.shields.io/badge/-🔬%20gowaite-0d1117?style=flat&logoColor=00ff41)](https://github.com/basil-eldho/gowaite) &nbsp;eBPF uprobes on Go's runtime scheduler — live goroutine anomaly detection + Prometheus metrics

[![C HTTP Server](https://img.shields.io/badge/-⚡%20C%20HTTP%20Server-0d1117?style=flat)](https://github.com/basil-eldho/c-http-server) &nbsp;HTTP/1.1 built from scratch on epoll + non-blocking I/O

**Infrastructure & Security**

[![5G CTF KubeVirt](https://img.shields.io/badge/-🛡️%205G%20CTF%20KubeVirt%20Testbed-0d1117?style=flat)](https://github.com/basil-eldho/5g-ctf-kubevirt) &nbsp;Security testing environment for 5G networks on KubeVirt

**Applications**

[![sleuth](https://img.shields.io/badge/-🐳%20sleuth-0d1117?style=flat)](https://github.com/basil-eldho/sleuth) &nbsp;Container lifecycle management with real-time WebSocket updates

[![DSAR Privacy App](https://img.shields.io/badge/-🔒%20DSAR%20Privacy%20App-0d1117?style=flat)](https://github.com/basil-eldho/dsar-app) &nbsp;Email ingestion, GDPR/CCPA-aware case management · Go + AWS SES

---

### `$ git log --stat`

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=basil-eldho&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&icon_color=00ff41&title_color=00ff41&border_color=00ff41"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=basil-eldho&layout=compact&langs_count=6&theme=github_dark&title_color=00ff41&border_color=00ff41"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=basil-eldho&theme=github-dark-blue&hide_border=false&ring=00ff41&fire=00ff41&currStreakLabel=00ff41"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=basil-eldho&theme=github-compact&hide_border=false&color=00ff41&line=00ff41&point=ffffff" width="95%"/>
</p>


<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff41,100:0d1117&height=100&section=footer" width="100%"/>
</div>
