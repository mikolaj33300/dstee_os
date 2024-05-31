Dit is de versie van OP-TEE OS met DS-TEE en aanpassingen hiervoor aan:  
-attestation.c  
-thread_a32.S  
-thread.c  
-thread.h  
-abort.c  
-abort.h  
-plat-vexpress/main.c  
-mk/config.mk  
Om de attestatie correct op de dstee TA te doen verlopen moet het taskset commando op QEMU beschikbaar zijn om de handlers en de TA op dezelfde core te laten uitvoeren  
