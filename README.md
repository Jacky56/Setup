# Setup
Setting up a new environment on new computer

## Programs

Critical programs:
- [vscode](https://code.visualstudio.com/)
- [wsl: ubuntu](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
- [python](https://www.python.org/downloads/)
- [gcloud utils](https://cloud.google.com/sdk/docs/install)

After you install the the above:
- [terraform](https://www.terraform.io/downloads.html)
- [docker](https://www.docker.com/get-started)
- [kubernetes](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- [minikube](https://minikube.sigs.k8s.io/docs/start/)

## linux

applications:
- brew
- fzf
- tmux

After you install wsl: ubuntu:
- [brew](https://medium.com/@edwardbaeg9/using-homebrew-on-windows-10-with-windows-subsystem-for-linux-wsl-c7f1792f88b3)

Run to install `tmux` & `fzf`:
```bash
brew install tmux
brew install fzf
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install
```

### tmux

First kill all running `tmux-servers`:
```bash
tmux kill-server
tmux ls
```
copy `.tmux.conf` to `~/` (home directory)

