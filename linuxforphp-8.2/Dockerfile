FROM asclinux/linuxforphp-8.2-ultimate:src
RUN echo "<?php phpinfo();" > /srv/www/index.php
RUN lfphp-compile "" nts
CMD ["/bin/bash"]
