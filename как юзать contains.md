# JAVA
Куски кода
for (int i = 0; i < list.size(); i++) {
                String s = list.get(i);
                if (s.contains("р") && s.contains("л") != true) {
                    list.remove(i);
                    i--;
                }
                if (s.contains("л") && s.contains("р") != true) {
                    list.add(0, s);
                    i++;
                }
