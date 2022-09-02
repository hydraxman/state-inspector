# Learning Results


| **Protocol**       | **Implementation** | **Classifying Memory (bytes : allocations)** | **Memory States** | **I/O States** | **Total Queries** | **Bootstrap Queries** | **Normal Queries** | **Watchpoint Queries** | **Watchpoint hits (pos : neg)** |
|--------------------|--------------------|----------------------------------------------|-------------------|----------------|-------------------|-----------------------|--------------------|------------------------|---------------------------------|
| TLS 1\.2 \- Server | OpenSSL 1\.0\.1g   | 94 : 6                                       | 21                | 13             | 621               | 100                   | 225                | 296                    | 177 \(0 : 177\)                 |
| TLS 1\.2 \- Server | OpenSSL 1\.0\.1j   |                                              |                   |                |                   |                       |                    |                        |                                 |
| TLS 1\.2 \- Server | OpenSSL 1\.0\.11   |                                              |                   |                |                   |                       |                    |                        |                                 |
| TLS 1\.2 \- Server | OpenSSL 1\.0\.2    |                                              |                   |                |                   |                       |                    |                        |                                 |
| TLS 1\.2 \- Server | Hostap TLS         | 159 : 32                                     | 11                | 6              | 194               | 60                    | 100                | 34                     | 17 \(0 : 17\)                   |
| TLS 1\.2 \- Server | GnuTLS 3\.3\.12    | 172 : 7                                      | 16                | 7              | 265               | 69                    | 160                | 36                     | 42 \(0 : 42\)                   |
|                    |                    |                                              |                   |                |                   |                       |                    |                        |                                 |
| TLS 1\.2 \- Server | GnuTLS 3\.5\.9     |                                              |                   |                |                   |                       |                    |                        |                                 |
| TLS 1\.2 \- Server | GnuTLS 3\.6\.14    |                                              |                   |                |                   |                       |                    |                        |                                 |
| TLS 1\.2 \- Server | GnuTLS 3\.6\.14    |                                              |                   |                |                   |                       |                    |                        |                                 |
| WPA/2 \- AP        | Hostap 2\.8        |                                              |                   |                |                   |                       |                    |                        |                                 |
| WPA/2 \- AP        | IWD 1\.6           |                                              |                   |                |                   |                       |                    |                        |                                 |
| WPA/2 \- AP        | IWD fixed          |                                              |                   |                |                   |                       |                    |                        |                                 |