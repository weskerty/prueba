        <h2>🐧 Linux a un Clic</h2>
        <p>Instalar Linux desde Windows fácilmente sin riesgos, manteniendo Windows con todos tus archivos.</p>
       <h2>💾 Simplemente descarga e instala <a href="https://master.dl.sourceforge.net/project/linuxoneclick/MiLinux.exe?viasf=1">este archivo ⬇️</a></h2>
        Relájate hasta que termine el proceso. Puedes hacer otras cosas mientras se instala, como navegar por Internet.</p>

        <h2>📹 Video Demostrativo</h2>
        <video src="https://github.com/user-attachments/assets/f729b276-0923-41c1-9bd5-7d44e5524a82" controls width="100%" height="auto"></video>
        <p>⏩ El video está acelerado, esto tardará dependiendo de tu PC.<br> 💽 Se requiere 35GB de espacio libre.<br> 🔓 Se requiere SecureBoot deshabilitado. En caso de tenerlo habilitado, el programa se instalará, pero al reiniciar iniciará Windows normalmente.</p>

        <h2>🔓 ¿Cómo Deshabilitar SecureBoot?</h2>
        <details>
            <summary>Pasos a seguir; ⬇️</summary>
            <h3>🔏 ¿Qué es SecureBoot?</h3>
            <p>SecureBoot es un sistema de seguridad que evita que programas no certificados puedan arrancar con el sistema. Lamentablemente, este script requiere tener SecureBoot desactivado ya que no está firmado por Microsoft.</p>

            <h4>👨‍💻 Desactivar SecureBoot desde BIOS</h4>
            <p>Para desactivar SecureBoot con este método, deberás reiniciar la PC, y cuando encienda, deberás pulsar la tecla `Setup` que aparece en pantalla. Suele ser `F2`, `F12` o `DEL`.<br>
            Luego busca a través de las flechas del teclado la sección `Sistema\System`, `Inicio\Boot`, `Seguridad` y en un submenú debe aparecer SecureBoot. Ajustarlo a apagado, guardar y reiniciar.<br>
            Esto varía por PC, aquí hay algunos ejemplos:</p>
            <p>
                <a href="https://www.dell.com/support/contents/es-mx/videos/videoplayer/how-to-enable-secure-boot/6333794882112?lwp=rt"><img src="https://img.shields.io/badge/dell-007DB8?style=for-the-badge&logo=dell&logoColor=white" alt="Dell" /></a>
                <a href="https://www.youtube.com/watch?v=8nxl-ZzjapA"><img src="https://img.shields.io/badge/Asus-black?style=for-the-badge&logo=asus&logoColor=white" alt="Asus" /></a>
                <a href="https://www.youtube.com/watch?v=fziNzTmiwPE"><img src="https://img.shields.io/badge/acer-83B81A?style=for-the-badge&logo=acer&logoColor=white" alt="Acer" /></a>
                <a href="https://www.youtube.com/watch?v=mh5mDCw5L4M"><img src="https://img.shields.io/badge/hp-0096D6?style=for-the-badge&logo=hp&logoColor=white" alt="HP" /></a>
                <a href="https://support.lenovo.com/cl/es/videos/nvid500424-disable-and-enable-secure-boot-in-bios-lenovo-support-quick-tips"><img src="https://img.shields.io/badge/lenovo-E2231A?style=for-the-badge&logo=lenovo&logoColor=white" alt="Lenovo" /></a>
                <a href="https://www.youtube.com/watch?v=4GPmc8QVCQE"><img src="https://img.shields.io/badge/samsung-1428A0?style=for-the-badge&logo=Samsung&logoColor=white" alt="Samsung" /></a>
                <a href="https://www.youtube.com/watch?v=EypQEavuO_8"><img src="https://img.shields.io/badge/MSI-FF0000?style=for-the-badge&logo=msi&logoColor=white" alt="MSI" /></a>
            </p>

            <details>
                <summary>Lenovo ThinkPad</summary>
                <p>Aquí 2 ejemplos:</p>
                <p>Versiones antiguas: <a href="https://youtu.be/_MeUEWgv8i4?t=146">https://youtu.be/_MeUEWgv8i4?t=146</a></p>
                <p>Versiones nuevas:</p>
                <video src="https://github.com/user-attachments/assets/1517bb59-abd1-43a2-9a51-0ef32ccd21db" controls width="100%" height="auto"></video>
            </details>

            <details>
                <summary>HP</summary>
                <p>Deberás reiniciar tu PC y cuando encienda, pulsar rápidamente la tecla `ESC` y aparecerá este menú:</p>
                <img src="https://github.com/user-attachments/assets/61ba5f8b-7b1d-4323-94c2-36a757129b33" alt="HP Menu">
                <p>Luego tendrás que elegir `F10` para abrir un menú gris. Con las flechas del teclado, debes ir a la sección "Seguridad del Sistema" y seleccionar "Opciones de Inicio".</p>
                <img src="https://github.com/user-attachments/assets/52cbe76b-4613-430e-840c-bf8828a8ebc8" alt="HP Security Menu">
                <p>Luego `Enter` en SecureBoot y ajustarlo a Desactivado.</p>
                <img src="https://github.com/user-attachments/assets/dc00844f-1067-47c1-afed-32c128222120" alt="HP Disable Secure Boot">
                <p>Ahora pulsa `F10` o ve a la sección Guardar y Reiniciar. Reinicia y listo.</p>
            </details>

            <details>
                <summary>Gigabyte</summary>
                <p>Deberás reiniciar y cuando encienda, pulsar la tecla `DEL` para mostrar el menú. Luego ir a la sección Sistema o BIOS y seleccionar SecureBoot:</p>
                <img src="https://github.com/user-attachments/assets/284ecb93-4284-42af-b042-0a15faf6a894" alt="Gigabyte Menu" width="350" height="240">
                <p>Luego seleccionar SecureBoot, enter y Disable/OFF.</p>
                <img src="https://github.com/user-attachments/assets/cbff9304-1fb4-455f-9808-a8ccc3c93659" alt="Gigabyte Disable Secure Boot" width="350" height="240">
                <p>Ahora ve a Guardar y Reiniciar.</p>
            </details>
        </details>

        <h2>🤨 ¿Qué le hace esto a mi PC?</h2>
        <p>El ejecutable descomprime todo esto en C:/MiLinux/<br>
        En caso de detectarse UEFI instala <a href="https://www.rodsbooks.com/refind/">rEFIndx64</a>.<br>
        En caso de detectarse BIOS instala <a href="https://sourceforge.net/projects/grub2win/">Grub2Win</a>.<br>
        Se agregan módulos como <a href="https://github.com/ventoy/vdiskchain">vdiskchain y ipxe</a> que son necesarios para el arranque VDI.<br>
        Se agrega un VDI de 25GB en C:/MiLinux/MiLinux.vtoy. Este es el disco Linux.<br>
        Se establece rEFInd o Grub2 como gestor de arranque.</p>

        <h2>🙋💖 Grupos de Ayuda Linux 🤗</h2>
        <h3>Español</h3>
        <p>
            <a href="https://www.facebook.com/groups/LinuxGroups/"><img src="https://img.shields.io/badge/Facebook-blue?logo=facebook&logoColor=fff&style=flat" alt="Facebook" /></a>
            <a href="https://chat.whatsapp.com/BsBW4RbEVpj8KO22AN2KDB"><img src="https://img.shields.io/badge/WhatsApp-25D366?logo=whatsapp&logoColor=fff&style=flat" alt="WhatsApp" /></a>
            <a href="https://t.me/addlist/pbpqO72i6x44MmQx"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=fat&logo=telegram&logoColor=white" alt="Telegram" /></a>
            <a href="https://discord.com/invite/XYYvqUF3pG"><img src="https://img.shields.io/badge/Discord-7289DA?style=fat&logo=discord&logoColor=white" alt="Discord" /></a>
        </p>

        <h3>PortuguêsBR</h3>
        <p>
            <a href="https://www.facebook.com/groups/brlinux/"><img src="https://img.shields.io/badge/Facebook-blue?logo=facebook&logoColor=fff&style=flat" alt="Facebook" /></a>
        </p>

        <h3>English</h3>
        <p>
            <a href="https://www.facebook.com/groups/GNUAndLinux/"><img src="https://img.shields.io/badge/Facebook-blue?logo=facebook&logoColor=fff&style=flat" alt="Facebook" /></a>
            <a href="https://discord.gg/mint"><img src="https://img.shields.io/badge/DiscordOfficial-87cf3e?style=fat&logo=discord&logoColor=white" alt="Discord" /></a>
            <a href="https://discord.gg/linux-for-all-304606245132697600"><img src="https://img.shields.io/badge/Discord2-7289DA?style=fat&logo=discord&logoColor=white" alt="Discord" /></a>
            <a href="https://www.reddit.com/r/linuxmint/"><img src="https://img.shields.io/badge/Reddit-FF5722?style=fat&logo=reddit&logoColor=white" alt="Reddit" /></a>
        </p>

        <h2>💢 ¿Errores?</h2>
        <p><a href="https://github.com/weskerty/LinuxOneClick/issues/new">Infórmalo aquí ↗️</a></p>

        <h2>🗑️ Desinstalación</h2>
        <details>
            <summary>Pasos a seguir; ⬇️</summary>
            <p>Simplemente ve a C:/MiLinux/uninstall.exe para desinstalarlo como se ve en este video:</p>
            <video src="https://github.com/user-attachments/assets/fd6e3b13-3232-413f-881e-e8c56e44b71d" controls width="100%" height="auto"></video>
            <p>Así de fácil.</p>
        </details>

        <h2>💿 Aumentar Tamaño de Almacenamiento Linux VHD</h2>
        <details>
            <summary>Pasos a seguir; ⬇️</summary>
            <p>Ir al archivo llamado "AddStorage.bat" que se encuentra en C:/MiLinux/ y ejecutarlo como administrador.<br>
            Luego escribe la cantidad que te gustaría en GB. Debe ser el tamaño total. Actualmente es 25GB, si quieres 5GB más, entonces escribes 30. Agregará 5GB más para que tenga 30GB.<br>
            Una vez completado el proceso, reinicia a Linux y abre el programa Discos, clic derecho sobre el disco EXT4 y reajustar tamaño. Luego mueve la barra para abarcar la totalidad de la memoria. Aceptar y listo.</p>
            <p>Video demostrativo:</p>
            <video src="https://github.com/user-attachments/assets/09c339b1-b39a-4bf6-be96-2147463ed04b" controls width="100%" height="auto"></video>
        </details>

        <h2><a href="https://linuxmint.com.es/">💟 Más información sobre Linux Mint ↗️</a></h2>

        <h2>🐧 MiLinux</h2>
        <p>En el VHD se realizó:</p>
        <ul>
        <li>Instalación OEM de Linux Mint</li>
        <li>Ejecución de <a href="https://github.com/ventoy/vtoyboot">vtoyBoot</a></li>
        <li><a href="https://es.wikipedia.org/wiki/GNU_GRUB">GRUB</a>; Agregado; VTOY_LINUX_REMOUNT=1 mitigations=off.</li>
        <li><a href="https://es.wikipedia.org/wiki/Fstab">FSTAB</a>; Agregado; relatime, nodiratime, noatime.</li>
        </ul>
        <p>Puedes reajustar estos detalles en sus respectivos archivos. En caso de molestarte mitigations solo bórralo. Usa el comando <code>sudo nano /etc/default/grub</code> y borra <code>mitigations=off</code>, guárdalo y luego actualiza grub con <code>sudo update-grub</code>.</p>

        <h2>🖥️ Esto funciona en</h2>
        <img src="https://github.com/user-attachments/assets/8ff47ebe-780f-4d4b-894f-779c0887d844" alt="WorkOnMiPCGG" width="100" height="60"/>
        <ul>
         <li>Windows XP 32 y 64 Bits (Oficial)</li>
         <li>Windows Vista 32 y 64 Bits</li>
         <li>Windows 7 32 y 64 Bits</li>
         <li>Windows 10 32 y 64 Bits</li>
        <li>Windows 11 23H3 64 Bits</li>
        </ul>
        <p>Nota: Aunque se instala en Windows de 32 Bits, el procesador debe ser compatible con 64 Bits para iniciar LinuxMint.<br>
        El script usa la partición C:/. Si esta no está disponible, no sucederá nada.</p>
        <p>Advertencia: La instalación dañará el boot de Windows XP en caso de que no sea WXP oficial. En caso de que Windows no vuelva a iniciar, pulsa el <a href="Guides/BootMenu/BootMenu.md">botón BootMenu ↗️</a> al instante que inicias tu PC. Luego elige WindowsBootLoader. Alternativamente, puedes usar un <a href="https://sergeistrelec.name/winpe-10-8-sergei-strelec-english/237-winpe-11-10-8-sergei-strelec-x86x64native-x86-20240711-english-version.html">disco de reparación ↗️</a> para iniciar Windows.</p>

        <h2>😐 ¿No te gusta Linux Mint? Instala otra distribución</h2>
        <details>
            <summary>Pasos a seguir; ⬇️</summary>
            <p>Puedes cambiar la instalación del VHD con VirtualBox y seguir la instalación correspondiente desde allí.<br>
            Descarga e instala VirtualBox en Windows <a href="https://www.virtualbox.org/wiki/Downloads">https://www.virtualbox.org/wiki/Downloads</a>.<br>
            Abre VirtualBox, clic en Nueva Máquina, ajusta el nombre y la ubicación de la ISO (medio de instalación). Luego ajusta los recursos que usará VirtualBox. DEBES MARCAR HABILITAR EFI. Luego seleccionas "Usar Disco Existente" y seleccionas el icono de carpeta para buscar la ubicación de MiLinux.vhd.vtoy, lo seleccionas y clic en Siguiente. Inicia la máquina virtual y instala tu distribución como de costumbre.</p>
        </details>

        <h2><a href="https://youtu.be/2mUI3CMjmMc?t=27">🐧 Instala Linux directamente ↗️</a></h2>

        <h2>💗 Se usó</h2>
        <p>
            <a href="https://sourceforge.net/projects/nsisbi/files/nsisbi3.04.1/"><img src="https://img.shields.io/badge/NSISMod-100000?style=for-the-badge&logo=github&logoColor=white" alt="NSISMod" /></a>
            <a href="https://7zip-es.updatestar.com/"><img src="https://img.shields.io/badge/7Zip-100000?style=for-the-badge&logo=github&logoColor=white" alt="7Zip" /></a>
            <a href="https://github.com/ventoy/vdiskchain"><img src="https://img.shields.io/badge/VDiskChain-100000?style=for-the-badge&logo=github&logoColor=white" alt="VDiskChain" /></a>
            <a href="https://sourceforge.net/projects/grub2win/files/"><img src="https://img.shields.io/badge/Grub2Win-100000?style=for-the-badge&logo=github&logoColor=white" alt="Grub2Win" /></a>
            <a href="https://www.rodsbooks.com/refind/"><img src="https://img.shields.io/badge/rEFInd-100000?style=for-the-badge&logo=github&logoColor=white" alt="rEFInd" /></a>
        </p>

        <p>Todos son libres de editar este mejunje de scripts.</p>
