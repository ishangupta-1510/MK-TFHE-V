cmake_minimum_required(VERSION 3.21)
project(testMK)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(testMK
        lagrangehalfc_arithmetic.h
        lwe-functions.h
        lwebootstrappingkey.h
        lwekey.h
        lwekeyswitch.h
        lweparams.h
        lwesamples.h
        mkTFHEfunctions.h
        mkTFHEkeygen.h
        mkTFHEkeys.h
        mkTFHEparams.h
        mkTFHEsamples.h
        numeric_functions.h
        polynomials.h
        polynomials_arithmetic.h
        testMKbootNAND_FFT_v2.cpp
        tfhe.h
        tfhe_core.h
        tfhe_garbage_collector.h
        tfhe_gate_bootstrapping_functions.h
        tfhe_gate_bootstrapping_structures.h
        tfhe_generic_streams.h
        tfhe_generic_templates.h
        tfhe_io.h
        tfhe_logic.h
        tgsw.h
        tgsw_functions.h
        tlwe.h
        tlwe_functions.h)
