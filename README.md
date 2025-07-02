To Pull Docker After opening Terminal;
Step 1: In the terminal to pull the Hazelcast container: "docker pull hazelcast/hazelcast:latest"
Step 2: To pull the Hazelcast Management Center container: After typing "docker pull hazelcast/management-center:latest"

Step 3: To Run Docker Containers: "docker run hazelcast/hazelcast:latest"
Step 4: To run Hazelcast Management Center: "docker run --rm -p 8080:8080 hazelcast/management-center:latest" to check if Hazelcast is working and to access Hazelcast Management Center, I typed
"http://localhost:8080" in my browser. If it is working correctly, you should see Hazelcast Management Center at this address.



Docker'ı Çekmek İçin Terminal açıldıktan sonra;
1. adım : Hazelcast konteynerını çekmek için terminale: "docker pull hazelcast/hazelcast:latest" kodunu yazdım
2. adım : Hazelcast Management Center konteynerını çekmek için:"docker pull hazelcast/management-center:latest" kodlarını yazdıktan sonra

3. adım olarak : Docker Konteynerlarını Çalıştırmak için:"docker run hazelcast/hazelcast:latest"
4. adım : Hazelcast Management Center'ı çalıştırmak için:"docker run --rm -p 8080:8080 hazelcast/management-center:latest" kodlarını yazdıktan sonra Hazelcast'in çalışıp çalışmadığını kontrol etmek için ve Hazelcast Management Center'a erişmek için tarayıcıma ;
"http://localhost:8080"  yazarak erişebildim. Eğer doğru şekilde çalışıyorsa, bu adreste Hazelcast Management Center'ı görmelisin.
