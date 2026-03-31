0      say-hello-inline-bash  say-hello-inline-bash  Hello World            01-hello-local.yml         workflow_dispatch
0      setup-e-lint           setup-e-lint           02-pipeline-principal  02-pipeline-principal.yml  push
1      testes-unitarios       testes-unitarios       02-pipeline-principal  02-pipeline-principal.yml  push
1      scan-de-seguranca      scan-de-seguranca      02-pipeline-principal  02-pipeline-principal.yml  push
2      build-e-deploy         build-e-deploy         02-pipeline-principal  02-pipeline-principal.yml  push

time="2026-03-31T10:13:16-03:00" level=info msg="Using docker host 'npipe:////./pipe/docker_engine', and daemon socket 'npipe:////./pipe/docker_engine'"
*DRYRUN* [02-pipeline-principal/setup-e-lint] ⭐ Run Set up job
*DRYRUN* [02-pipeline-principal/setup-e-lint] 🚀  Start image=catthehacker/ubuntu:act-latest
*DRYRUN* [02-pipeline-principal/setup-e-lint]   🐳  docker pull image=catthehacker/ubuntu:act-latest platform= username= forcePull=true
*DRYRUN* [02-pipeline-principal/setup-e-lint]   🐳  docker create image=catthehacker/ubuntu:act-latest platform= entrypoint=["tail" "-f" "/dev/null"] cmd=[] network="host"
*DRYRUN* [02-pipeline-principal/setup-e-lint]   🐳  docker run image=catthehacker/ubuntu:act-latest platform= entrypoint=["tail" "-f" "/dev/null"] cmd=[] network="host"
*DRYRUN* [02-pipeline-principal/setup-e-lint]   ✅  Success - Set up job
*DRYRUN* [02-pipeline-principal/setup-e-lint] ⭐ Run Main Setup e lint
*DRYRUN* [02-pipeline-principal/setup-e-lint]   ✅  Success - Main Setup e lint [112.8602ms]
*DRYRUN* [02-pipeline-principal/setup-e-lint] ⭐ Run Complete job
*DRYRUN* [02-pipeline-principal/setup-e-lint] Cleaning up container for job setup-e-lint
*DRYRUN* [02-pipeline-principal/setup-e-lint]   ✅  Success - Complete job
*DRYRUN* [02-pipeline-principal/setup-e-lint] 🏁  Job succeeded
*DRYRUN* [02-pipeline-principal/scan-de-seguranca] ⭐ Run Set up job
*DRYRUN* [02-pipeline-principal/testes-unitarios ] ⭐ Run Set up job
*DRYRUN* [02-pipeline-principal/scan-de-seguranca] 🚀  Start image=catthehacker/ubuntu:act-latest
*DRYRUN* [02-pipeline-principal/testes-unitarios ] 🚀  Start image=catthehacker/ubuntu:act-latest
*DRYRUN* [02-pipeline-principal/testes-unitarios ]   🐳  docker pull image=catthehacker/ubuntu:act-latest platform= username= forcePull=true
*DRYRUN* [02-pipeline-principal/scan-de-seguranca]   🐳  docker pull image=catthehacker/ubuntu:act-latest platform= username= forcePull=true
*DRYRUN* [02-pipeline-principal/testes-unitarios ]   🐳  docker create image=catthehacker/ubuntu:act-latest platform= entrypoint=["tail" "-f" "/dev/null"] cmd=[] network="host"
*DRYRUN* [02-pipeline-principal/testes-unitarios ]   🐳  docker run image=catthehacker/ubuntu:act-latest platform= entrypoint=["tail" "-f" "/dev/null"] cmd=[] network="host"
*DRYRUN* [02-pipeline-principal/testes-unitarios ]   ✅  Success - Set up job
*DRYRUN* [02-pipeline-principal/scan-de-seguranca]   🐳  docker create image=catthehacker/ubuntu:act-latest platform= entrypoint=["tail" "-f" "/dev/null"] cmd=[] network="host"
*DRYRUN* [02-pipeline-principal/scan-de-seguranca]   🐳  docker run image=catthehacker/ubuntu:act-latest platform= entrypoint=["tail" "-f" "/dev/null"] cmd=[] network="host"
*DRYRUN* [02-pipeline-principal/scan-de-seguranca]   ✅  Success - Set up job
*DRYRUN* [02-pipeline-principal/scan-de-seguranca] ⭐ Run Main Scan de seguranca
*DRYRUN* [02-pipeline-principal/testes-unitarios ] ⭐ Run Main Testes unitarios
*DRYRUN* [02-pipeline-principal/testes-unitarios ]   ✅  Success - Main Testes unitarios [196.2574ms]
*DRYRUN* [02-pipeline-principal/scan-de-seguranca]   ✅  Success - Main Scan de seguranca [202.3657ms]
*DRYRUN* [02-pipeline-principal/testes-unitarios ] ⭐ Run Complete job
*DRYRUN* [02-pipeline-principal/scan-de-seguranca] ⭐ Run Complete job
*DRYRUN* [02-pipeline-principal/testes-unitarios ] Cleaning up container for job testes-unitarios
*DRYRUN* [02-pipeline-principal/scan-de-seguranca] Cleaning up container for job scan-de-seguranca
*DRYRUN* [02-pipeline-principal/testes-unitarios ]   ✅  Success - Complete job
*DRYRUN* [02-pipeline-principal/scan-de-seguranca]   ✅  Success - Complete job
*DRYRUN* [02-pipeline-principal/testes-unitarios ] 🏁  Job succeeded
*DRYRUN* [02-pipeline-principal/scan-de-seguranca] 🏁  Job succeeded
*DRYRUN* [02-pipeline-principal/build-e-deploy   ] ⭐ Run Set up job
*DRYRUN* [02-pipeline-principal/build-e-deploy   ] 🚀  Start image=catthehacker/ubuntu:act-latest
*DRYRUN* [02-pipeline-principal/build-e-deploy   ]   🐳  docker pull image=catthehacker/ubuntu:act-latest platform= username= forcePull=true
*DRYRUN* [02-pipeline-principal/build-e-deploy   ]   🐳  docker create image=catthehacker/ubuntu:act-latest platform= entrypoint=["tail" "-f" "/dev/null"] cmd=[] network="host"
*DRYRUN* [02-pipeline-principal/build-e-deploy   ]   🐳  docker run image=catthehacker/ubuntu:act-latest platform= entrypoint=["tail" "-f" "/dev/null"] cmd=[] network="host"
*DRYRUN* [02-pipeline-principal/build-e-deploy   ]   ✅  Success - Set up job
*DRYRUN* [02-pipeline-principal/build-e-deploy   ] ⭐ Run Main Build e deploy
*DRYRUN* [02-pipeline-principal/build-e-deploy   ]   ✅  Success - Main Build e deploy [160.9501ms]
*DRYRUN* [02-pipeline-principal/build-e-deploy   ] ⭐ Run Complete job
*DRYRUN* [02-pipeline-principal/build-e-deploy   ] Cleaning up container for job build-e-deploy
*DRYRUN* [02-pipeline-principal/build-e-deploy   ]   ✅  Success - Complete job
*DRYRUN* [02-pipeline-principal/build-e-deploy   ] 🏁  Job succeeded

