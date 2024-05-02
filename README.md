# envs-ansible
環境構築のためのansible

## usage
すべてのホストに対し、playbookを実行する。
```
$ ansible-playbook -i hosts playbooks/install-oh-my-zsh.yml
```
特定のホストに対し、playbookを実行する。
```
$ ansible-playbook -i hosts -l work01.srv.tdn.home.440kbase.jp playbooks/install-oh-my-zsh.yml
```
