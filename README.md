# JavaStream

////to print elements in upper case which ends with "m"
Stream.of("Ram","Sham","John","James","julie","Andrew").filter(s->s.endsWith("m")).map(s->s.toUpperCase()).forEach(s->System.out.println(s));
