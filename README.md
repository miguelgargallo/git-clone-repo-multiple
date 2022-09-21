# git-clone-repo-multiple

        xargs -L1 git clone <<EOF
        link
        link
        link
        link
        link
        link
        link
        link
        link
        EOF


Example:

                        $ xargs -L1 git clone <<EOF
                        > https://github.com/llop/penrose-triangle-js
                        > https://github.com/llop/mandelbrot-viewer-js
                        > https://github.com/llop/ide-jutge-local
                        > https://github.com/llop/Degree-Final-Project-FIB-UPC
                        > https://github.com/llop/joc-eda-bola-de-drac
                        > https://github.com/llop/Pacman-3D-World
                        > https://github.com/llop/GRAU-EDA
                        > https://github.com/llop/GRAU-CAP
                        > https://github.com/llop/GRAU-A
                        > https://github.com/llop/GRAU-SID
                        > https://github.com/llop/GRAU-G
                        > https://github.com/llop/GRAU-AC
                        > https://github.com/llop/GRAU-LI
                        > https://github.com/llop/GRAU-LP
                        > https://github.com/llop/GRAU-PRO2
                        > https://github.com/llop/GRAU-IDI
                        > https://github.com/llop/R-Type
                        > https://github.com/llop/gdb-mi-parser
                        > https://github.com/llop/jutge-python
                        > https://github.com/llop/GdbScript
                        > https://github.com/llop/hummingbird-MOGL
                        > https://github.com/llop/web-ide
                        > https://github.com/llop/gdb-mi
                        > https://github.com/llop/porra-joc-eda
                        > https://github.com/llop/llop_blog
                        > EOF
                        Cloning into 'penrose-triangle-js'...
                        remote: Enumerating objects: 48, done.
                        remote: Total 48 (delta 0), reused 0 (delta 0), pack-reused 48
                        Receiving objects: 100% (48/48), 70.81 KiB | 993.00 KiB/s, done.
                        Resolving deltas: 100% (23/23), done.
                        Cloning into 'mandelbrot-viewer-js'...
                        remote: Enumerating objects: 35, done.
                        remote: Total 35 (delta 0), reused 0 (delta 0), pack-reused 35
                        Receiving objects: 100% (35/35), 13.14 KiB | 464.00 KiB/s, done.
                        Resolving deltas: 100% (18/18), done.
                        Cloning into 'ide-jutge-local'...
                        remote: Enumerating objects: 1261, done.
                        remote: Total 1261 (delta 0), reused 0 (delta 0), pack-reused 1261
                        Receiving objects: 100% (1261/1261), 5.05 MiB | 6.07 MiB/s, done.
                        Resolving deltas: 100% (621/621), done.
                        Cloning into 'Degree-Final-Project-FIB-UPC'...
                        remote: Enumerating objects: 19, done.
                        remote: Total 19 (delta 0), reused 0 (delta 0), pack-reused 19
                        Receiving objects: 100% (19/19), 4.09 MiB | 7.34 MiB/s, done.
                        Resolving deltas: 100% (6/6), done.
                        Cloning into 'joc-eda-bola-de-drac'...
                        remote: Enumerating objects: 12, done.
                        remote: Total 12 (delta 0), reused 0 (delta 0), pack-reused 12
                        Receiving objects: 100% (12/12), 610.26 KiB | 2.80 MiB/s, done.
                        Resolving deltas: 100% (2/2), done.
                        Cloning into 'Pacman-3D-World'...
                        remote: Enumerating objects: 3558, done.
                        remote: Total 3558 (delta 0), reused 0 (delta 0), pack-reused 3558
                        Receiving objects: 100% (3558/3558), 302.99 MiB | 5.45 MiB/s, done.
                        Resolving deltas: 100% (1920/1920), done.
                        Updating files: 100% (1791/1791), done.
                        Cloning into 'GRAU-EDA'...
                        remote: Enumerating objects: 43, done.
                        remote: Total 43 (delta 0), reused 0 (delta 0), pack-reused 43
                        Receiving objects: 100% (43/43), 566.85 KiB | 2.50 MiB/s, done.
                        Resolving deltas: 100% (6/6), done.
                        Cloning into 'GRAU-CAP'...
                        remote: Enumerating objects: 15, done.
                        remote: Total 15 (delta 0), reused 0 (delta 0), pack-reused 15
                        Receiving objects: 100% (15/15), 466.92 KiB | 2.16 MiB/s, done.
                        Resolving deltas: 100% (4/4), done.
                        Cloning into 'GRAU-A'...
                        remote: Enumerating objects: 126, done.
                        remote: Total 126 (delta 0), reused 0 (delta 0), pack-reused 126
                        Receiving objects: 100% (126/126), 14.09 MiB | 2.36 MiB/s, done.
                        Resolving deltas: 100% (8/8), done.
                        Cloning into 'GRAU-SID'...
                        remote: Enumerating objects: 47, done.
                        remote: Total 47 (delta 0), reused 0 (delta 0), pack-reused 47
                        Receiving objects: 100% (47/47), 334.45 KiB | 1.82 MiB/s, done.
                        Resolving deltas: 100% (7/7), done.
                        Cloning into 'GRAU-G'...
                        remote: Enumerating objects: 409, done.
                        remote: Total 409 (delta 0), reused 0 (delta 0), pack-reused 409
                        Receiving objects: 100% (409/409), 151.69 KiB | 1.22 MiB/s, done.
                        Resolving deltas: 100% (139/139), done.
                        Cloning into 'GRAU-AC'...
                        remote: Enumerating objects: 93, done.
                        remote: Total 93 (delta 0), reused 0 (delta 0), pack-reused 93
                        Receiving objects: 100% (93/93), 535.48 KiB | 2.41 MiB/s, done.
                        Resolving deltas: 100% (27/27), done.
                        Cloning into 'GRAU-LI'...
                        remote: Enumerating objects: 100, done.
                        remote: Total 100 (delta 0), reused 0 (delta 0), pack-reused 100
                        Receiving objects: 100% (100/100), 67.99 KiB | 881.00 KiB/s, done.
                        Resolving deltas: 100% (10/10), done.
                        Cloning into 'GRAU-LP'...
                        remote: Enumerating objects: 112, done.
                        remote: Counting objects: 100% (112/112), done.
                        remote: Compressing objects: 100% (94/94), done.
                        remote: Total 112 (delta 15), reused 112 (delta 15), pack-reused 0
                        Receiving objects: 100% (112/112), 622.49 KiB | 1.23 MiB/s, done.
                        Resolving deltas: 100% (15/15), done.
                        Cloning into 'GRAU-PRO2'...
                        remote: Enumerating objects: 157, done.
                        remote: Total 157 (delta 0), reused 0 (delta 0), pack-reused 157
                        Receiving objects: 100% (157/157), 80.40 KiB | 980.00 KiB/s, done.
                        Resolving deltas: 100% (37/37), done.
                        Cloning into 'GRAU-IDI'...
                        remote: Enumerating objects: 38, done.
                        remote: Total 38 (delta 0), reused 0 (delta 0), pack-reused 38
                        Receiving objects: 100% (38/38), 1.20 MiB | 4.09 MiB/s, done.
                        Resolving deltas: 100% (9/9), done.
                        Cloning into 'R-Type'...
                        remote: Enumerating objects: 937, done.
                        remote: Total 937 (delta 0), reused 0 (delta 0), pack-reused 937
                        Receiving objects: 100% (937/937), 195.61 MiB | 7.76 MiB/s, done.
                        Resolving deltas: 100% (611/611), done.
                        Cloning into 'gdb-mi-parser'...
                        remote: Enumerating objects: 29, done.
                        remote: Total 29 (delta 0), reused 0 (delta 0), pack-reused 29
                        Receiving objects: 100% (29/29), 5.70 KiB | 2.85 MiB/s, done.
                        Resolving deltas: 100% (10/10), done.
                        Cloning into 'jutge-python'...
                        remote: Enumerating objects: 83, done.
                        remote: Total 83 (delta 0), reused 0 (delta 0), pack-reused 83
                        Receiving objects: 100% (83/83), 14.18 KiB | 427.00 KiB/s, done.
                        Resolving deltas: 100% (35/35), done.
                        Cloning into 'GdbScript'...
                        remote: Enumerating objects: 57, done.
                        remote: Total 57 (delta 0), reused 0 (delta 0), pack-reused 57
                        Receiving objects: 100% (57/57), 70.08 KiB | 824.00 KiB/s, done.
                        Resolving deltas: 100% (20/20), done.
                        Cloning into 'hummingbird-MOGL'...
                        remote: Enumerating objects: 199, done.
                        remote: Total 199 (delta 0), reused 0 (delta 0), pack-reused 199
                        Receiving objects: 100% (199/199), 36.36 KiB | 979.00 KiB/s, done.
                        Resolving deltas: 100% (110/110), done.
                        Cloning into 'web-ide'...
                        remote: Enumerating objects: 2453, done.
                        remote: Total 2453 (delta 0), reused 0 (delta 0), pack-reused 2453
                        Receiving objects: 100% (2453/2453), 7.84 MiB | 5.31 MiB/s, done.
                        Resolving deltas: 100% (738/738), done.
                        Cloning into 'gdb-mi'...
                        remote: Enumerating objects: 32, done.
                        remote: Total 32 (delta 0), reused 0 (delta 0), pack-reused 32
                        Receiving objects: 100% (32/32), 14.50 KiB | 464.00 KiB/s, done.
                        Resolving deltas: 100% (14/14), done.
                        Cloning into 'porra-joc-eda'...
                        remote: Enumerating objects: 473, done.
                        remote: Total 473 (delta 0), reused 0 (delta 0), pack-reused 473
                        Receiving objects: 100% (473/473), 435.34 KiB | 2.11 MiB/s, done.
                        Resolving deltas: 100% (182/182), done.
                        Cloning into 'llop_blog'...
                        remote: Enumerating objects: 1515, done.
                        remote: Total 1515 (delta 0), reused 0 (delta 0), pack-reused 1515
                        Receiving objects: 100% (1515/1515), 45.81 MiB | 10.47 MiB/s, done.
                        Resolving deltas: 100% (785/785), done.
