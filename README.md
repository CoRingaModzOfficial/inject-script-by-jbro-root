Para Jogos Grandes igual Free fire

public static Void CMODS(int offSet, String Hex) {
        byte[] bytes = null;
        try (RandomAccessFile raf = new RandomAccessFile(/proc/" + pid + "/mem, "rw");
             FileChannel channel = raf.getChannel()) {
            ByteBuffer buff = ByteBuffer.wrap(hex2b(hex_t));

            for (int i = 0; i < addrs.size(); i++) {
                channel.write(buff, 0L + offSet);
            }

        } catch (Exception e) {
            System.out.println("Memory Inject no Completed");
            e.printStackTrace();
        }
    }
