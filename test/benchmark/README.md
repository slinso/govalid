# Benchmark Results

Performance comparison between govalid and popular Go validation libraries.

## Latest Results

**Benchmarked on:** 2025-12-30  
**Platform:** Linux 6.11.0-1018-azure x86_64  
**Go version:** go1.24.3

## Raw Benchmark Data

```
BenchmarkGoValidAlpha-4                    	124232311	         9.657 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundAlpha-4               	 2576572	       469.5 ns/op	       0 B/op	       0 allocs/op
BenchmarkAsaskevichGovalidatorAlpha-4      	11166507	       108.2 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateAlpha-4             	   52022	     22323 ns/op	   16937 B/op	     101 allocs/op
BenchmarkGoValidCELConcurrent-4            	653040156	         1.839 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELMultipleExpressions-4   	295620848	         4.062 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELBasic-4                 	295769181	         4.056 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELCrossField-4            	318218727	         3.753 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELStringLength-4          	1000000000	         1.000 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELNumericComparison-4     	1000000000	         1.000 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidEmail-4                    	21653884	        57.43 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundEmail-4               	 1000000	      1097 ns/op	      89 B/op	       5 allocs/op
BenchmarkGoValidatorEmail-4                	 1238707	       958.4 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateEmail-4             	   69004	     17239 ns/op	   15878 B/op	      76 allocs/op
BenchmarkGoValidEnum-4                     	256886574	         4.673 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidGT-4                       	427576070	         2.807 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundGT-4                  	11157646	       108.8 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorGT-4                   	13552615	        88.26 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidGTE-4                      	427588087	         2.840 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundGTE-4                 	10702656	       112.3 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidIPV4-4                     	30793981	        39.88 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundIPV4-4                	 9006532	       133.7 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidIPV6-4                     	14027281	        85.28 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundIPV6-4                	 6840204	       175.3 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidLength-4                   	144209421	         8.309 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundLength-4              	 9982593	       120.5 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorLength-4               	 4794735	       250.6 ns/op	      32 B/op	       2 allocs/op
BenchmarkGookitValidateLength-4            	   73146	     16280 ns/op	   15616 B/op	      79 allocs/op
BenchmarkGoValidLT-4                       	424249706	         2.811 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundLT-4                  	11295694	       106.0 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidLTE-4                      	384906234	         3.118 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundLTE-4                 	11211476	       107.3 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidMaxItems-4                 	202519916	         5.927 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMaxItems-4            	 8190688	       146.2 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidMaxLength-4                	32625303	        31.97 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMaxLength-4           	 8500514	       143.2 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorMaxLength-4            	 4194297	       287.5 ns/op	      32 B/op	       2 allocs/op
BenchmarkGookitValidateMaxLength-4         	   72444	     16541 ns/op	   15648 B/op	      81 allocs/op
BenchmarkGoValidMinItems-4                 	175118448	         6.851 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMinItems-4            	 8537589	       141.1 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidMinLength-4                	48729228	        24.61 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMinLength-4           	10059164	       119.7 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorMinLength-4            	 4214528	       284.4 ns/op	      32 B/op	       2 allocs/op
BenchmarkGoValidNumeric-4                  	124348632	         9.652 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundNumeric-4             	13542841	        88.46 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorNumeric-4              	 9359215	       128.4 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateNumeric-4           	   70398	     16902 ns/op	   15574 B/op	      78 allocs/op
BenchmarkGoValidRequired-4                 	296146916	         4.047 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundRequired-4            	 7974913	       150.6 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorRequired-4             	641349991	         1.870 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateRequired-4          	   75742	     15808 ns/op	   15488 B/op	      73 allocs/op
BenchmarkGoValidURL-4                      	20747922	        57.71 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundURL-4                 	 2491394	       482.4 ns/op	     144 B/op	       1 allocs/op
BenchmarkGoValidatorURL-4                  	   95368	     11830 ns/op	     146 B/op	       1 allocs/op
BenchmarkGookitValidateURL-4               	   70450	     17064 ns/op	   15681 B/op	      77 allocs/op
BenchmarkGoValidUUID-4                     	21221395	        55.78 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundUUID-4                	 2667966	       450.4 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorUUID-4                 	 3559826	       336.7 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateUUID-4              	   69234	     17030 ns/op	   15542 B/op	      76 allocs/op
```

## Performance Comparison

| Validator | govalid | go-playground | vs go-playground | asaskevich/govalidator | vs asaskevich | gookit/validate | vs gookit |
|-----------|---------|---------------|------------------|----------------------|---------------|----------------|----------|
| LTE | 3.118 / 0 allocs | 107.3 / 0 allocs | **34.4x** | N/A | N/A | N/A | N/A |
| Enum | 4.673 / 0 allocs | N/A | N/A | N/A | N/A | N/A | N/A |
| Email | 57.43 / 0 allocs | 1097 / 89 B / 5 allocs | **19.1x** | 958.4 / 0 allocs | **16.7x** | 17239 / 15878 B / 76 allocs | **300.2x** |
| GTE | 2.840 / 0 allocs | 112.3 / 0 allocs | **39.5x** | N/A | N/A | N/A | N/A |
| MinLength | 24.61 / 0 allocs | 119.7 / 0 allocs | **4.9x** | 284.4 / 32 B / 2 allocs | **11.6x** | N/A | N/A |
| UUID | 55.78 / 0 allocs | 450.4 / 0 allocs | **8.1x** | 336.7 / 0 allocs | **6.0x** | 17030 / 15542 B / 76 allocs | **305.3x** |
| MaxItems | 5.927 / 0 allocs | 146.2 / 0 allocs | **24.7x** | N/A | N/A | N/A | N/A |
| MaxLength | 31.97 / 0 allocs | 143.2 / 0 allocs | **4.5x** | 287.5 / 32 B / 2 allocs | **9.0x** | 16541 / 15648 B / 81 allocs | **517.4x** |
| LT | 2.811 / 0 allocs | 106.0 / 0 allocs | **37.7x** | N/A | N/A | N/A | N/A |
| MinItems | 6.851 / 0 allocs | 141.1 / 0 allocs | **20.6x** | N/A | N/A | N/A | N/A |
| Alpha | 9.657 / 0 allocs | 469.5 / 0 allocs | **48.6x** | 108.2 / 0 allocs | **11.2x** | 22323 / 16937 B / 101 allocs | **2311.6x** |
| Required | 4.047 / 0 allocs | 150.6 / 0 allocs | **37.2x** | 1.870 / 0 allocs | **0.5x** | 15808 / 15488 B / 73 allocs | **3906.1x** |
| IPV4 | 39.88 / 0 allocs | 133.7 / 0 allocs | **3.4x** | N/A | N/A | N/A | N/A |
| Length | 8.309 / 0 allocs | 120.5 / 0 allocs | **14.5x** | 250.6 / 32 B / 2 allocs | **30.2x** | 16280 / 15616 B / 79 allocs | **1959.3x** |
| IPV6 | 85.28 / 0 allocs | 175.3 / 0 allocs | **2.1x** | N/A | N/A | N/A | N/A |
| URL | 57.71 / 0 allocs | 482.4 / 144 B / 1 allocs | **8.4x** | 11830 / 146 B / 1 allocs | **205.0x** | 17064 / 15681 B / 77 allocs | **295.7x** |
| Numeric | 9.652 / 0 allocs | 88.46 / 0 allocs | **9.2x** | 128.4 / 0 allocs | **13.3x** | 16902 / 15574 B / 78 allocs | **1751.1x** |
| GT | 2.807 / 0 allocs | 108.8 / 0 allocs | **38.8x** | 88.26 / 0 allocs | **31.4x** | N/A | N/A |

## CEL Expression Validation (govalid Exclusive)

| CEL Validator | govalid (ns/op) | Allocations |
|---------------|-----------------|-------------|
| CELConcurrent | 1.839 | 0 allocs |
| CELMultipleExpressions | 4.062 | 0 allocs |
| CELBasic | 4.056 | 0 allocs |
| CELCrossField | 3.753 | 0 allocs |
| CELStringLength | 1.000 | 0 allocs |
| CELNumericComparison | 1.000 | 0 allocs |

CEL (Common Expression Language) support allows complex runtime expressions with near-zero overhead.

## Running Benchmarks

```bash
# Update all benchmark documentation
make sync-benchmarks

# Run benchmarks manually
cd test
go test ./benchmark/ -bench=. -benchmem -benchtime=10s

# Run specific validator benchmarks
go test ./benchmark/ -bench=BenchmarkGoValid{ValidatorName} -benchmem
```
