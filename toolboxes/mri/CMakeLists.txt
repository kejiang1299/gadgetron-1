add_subdirectory(pmri)

if (ARMADILLO_FOUND)
   add_subdirectory(epi)
   if (CUDA_FOUND)
      add_subdirectory(hyper)
   endif(CUDA_FOUND)
endif (ARMADILLO_FOUND)

