1. 主要是加這行：HAL_ADC_Start_DMA(&hadc1, (uint32_t*)sample_buffer, SAMPLE_BUFFER_SIZE);
2. 還有 interrupt handler，讓他可以 eventqueue.call(print function)
