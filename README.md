<!-- markdownlint-disable MD033 MD041 -->
<div align="center">
    <h1>Provoz a údržba infrastruktury pro školní projekty</h1>
    <p>Maturitní práce</p>
</div>
<!-- markdownlint-enable MD033 MD041 -->

# Nasazení

1) Nainstalujte Alpine Linux podle answerfile z repozitáře (`setup-alpine -f https://gitlab.stepanse.dev/stepanse/maturitni-prace/-/raw/main/setup-answerfile/FILENAME`)
2) Nainstalujte na systém Python (`apk add python3`)
3) Přidejte hosta do `/ansible/inventory/hosts.yml`
4) Spusťe Ansible ze složky `/ansible/` (`ansible-playbook -i inventory/hosts.yml playbook.yml`)
