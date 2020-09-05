commit 380849cd117585fcfee6322b6c39e243b0bffbca
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 4 11:16:32 2020 -0400

    Added configure_postfix: true for Molecule
    
    - This will ensure that we test configurations
    - This also resolves the issue of the service not starting for RedHat distros when testing w/Molecule

commit 9f51e55b996b7bd7627ee634d351648ffc3663ab
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 4 10:41:23 2020 -0400

    Updated Molecule tests

commit b8244b9d074e2c79c3cbd83d2f4a7de752247af9
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 4 10:41:09 2020 -0400

    Fixed linting issues

commit ef2c0b4c08736cef98ae1d559e586f72a97b7c5e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 4 10:40:38 2020 -0400

    Updated CI Tests

commit 28cb0b7ac65226f4f6f1e348619de74d6441622e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 4 10:39:22 2020 -0400

    Updated Python requirements

commit fa0135a616a4997abab162b3e8238e0a885fcf4e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Apr 6 14:41:58 2020 -0400

    Testing with config postfix true

commit dd08f1006dc8e4dfccf06dc25ef3392b30c2dd86
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Apr 6 14:41:36 2020 -0400

    Broke tasks out from main

commit 08dba004c20adc9b8da4673c6d9cab9439bbcae8
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Apr 6 13:45:16 2020 -0400

    Cleaned up tasks, etc.

commit 6a3a4f84b1dfcf363d06007743f8892f5ff3a340
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Apr 6 13:35:43 2020 -0400

    Updated files, etc. after new structure
    
    This aligns to cookiecutter template

commit 037b982c77e09536b77182ff3700491b742270c2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Apr 6 13:31:26 2020 -0400

    Added: New files, etc. from cookiecutter template

commit 2dd70051f5a2e5103e9f7757413d21b079f20f57
Author: blaisep <blaise@gmail.com>
Date:   Sun Dec 23 22:34:39 2018 -0800

    Adjust the apt tasks to comply with the new, post v2.11 way of dealing with items.

commit bc9b65d290bd4f2dd81d1f62f4042dc6e4ba9075
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Feb 8 15:24:53 2018 -0500

    Changed state: running to state: started per issue #8

commit 702a72424bd8c28a77e3ed93695c7602b7837876
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Feb 1 13:15:56 2018 -0500

    Resolves #6

commit b9fdf998b2d1838057e60561538c25377662b57c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Apr 19 15:49:10 2017 -0400

    Cleaned up code
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 58fc60618f11c745376722f01738fa886931de13
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Apr 19 15:32:13 2017 -0400

    Added Travis testing
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 6fdff51152b3911511c6a54aac39db048fb26dab
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Apr 11 10:16:05 2017 -0400

    Added conditional to not restart service in check mode
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 65ca18b3dec87e3c124288f812ae851331f48127
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Apr 11 09:57:14 2017 -0400

    Cleaned up formatting and added conditional for service when running check mode
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit ea97b4ef32fcdf03175b3ce1389aeb2df5a2b8e9
Author: Nigel Gibbs <nigel@gibbsoft.com>
Date:   Wed Jul 27 15:49:33 2016 +0100

    Add support for enable_always_add_missing_headers

commit 112f3e168c90f2fc557fdcdd8b8a05802ed7e017
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed May 25 15:22:23 2016 -0400

    Updated Galaxy info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit cbfd70ab98d45a361646635f0bd34009018df554
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed May 25 15:21:20 2016 -0400

    Fixed Fedora install
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 09a5a0dbda02a0f44e01c4079c3fd875400066ae
Author: Nigel Gibbs <nigel@gibbsoft.com>
Date:   Wed Mar 9 09:41:26 2016 +0000

    Add paths for TLS certs

commit 20c5bf9cb3d622ead2aec399060379a36c5cc6be
Author: Nigel Gibbs <nigel@gibbsoft.com>
Date:   Mon Mar 7 13:43:03 2016 +0000

    Template canonical maps. Add support for changing helo hostname

commit dcc4ee899c07ebbb4a427039ecb2eb2fbc051928
Author: Nigel Gibbs <nigel@gibbsoft.com>
Date:   Sat Mar 5 13:59:04 2016 +0000

    Add support for sender_canonical maps.  Add support for alternative generic.j2 template.  Add some missing handler notifies.

commit 5b4579dc023a6f7b3911b756481d981d8adaf279
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Sun Aug 2 21:56:33 2015 -0400

    updated for CentOS6

commit 900f6285e202f25572678a58c50e780ddc597fc5
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Jul 29 22:20:29 2015 -0400

    added CentOS

commit ebf220285d688ccd3bff89a22db2a02d534b97dc
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Jul 29 22:08:20 2015 -0400

    fixing task formatting

commit d34979c35089cf0611eaa4a179e64624f395463a
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Jul 29 22:06:52 2015 -0400

    added when check for configure postfix

commit 53116fdd8dcfc091e421e0fe98c490bb3d4270ed
Author: Larry Smith Jr <larry.e.smith.jr@gmail.com>
Date:   Wed Jul 29 22:02:00 2015 -0400

    first commit
