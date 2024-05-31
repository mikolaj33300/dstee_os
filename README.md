Dit is de versie van OP-TEE OS met DS-TEE en aanpassingen hiervoor aan:  
-attestation.c  
-thread_a32.S  
-thread.c  
-thread.h  
-abort.c  
-abort.h  
-plat-vexpress/main.c  
-mk/config.mk  
Om de attestatie correct op de DSTEE TA te doen verlopen zou het "taskset" commando op QEMU gebruikt kunnen worden om TA op dezelfde core te laten uitvoeren als de attestatie in de interrupt handlers.

