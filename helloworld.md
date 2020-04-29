        /**
         * case中如果没有break，匹配到正确的case后，其后的case匹配不上也会执行
         * result: 23default
         */
        switch (2) {
            case 1:
                System.out.print(1);
            case 2:
                System.out.print(2);
            case 3:
                System.out.print(3);
            default:
                System.out.println("default");
        }
