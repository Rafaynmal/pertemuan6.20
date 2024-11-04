package pertemuan6;

/**
 *
 * @author Afra Syavina
 */
import java.text.DecimalFormat;

public class TargetSaldoTabungan {
    public static void main(String[] args) {
        double saldoAwal = 3500000;
        double bunga = 0.08; // 8%
        double saldoTarget = 6000000;
        DecimalFormat df = new DecimalFormat("#,###");

        int bulan = 0;
        while (saldoAwal < saldoTarget) {
            saldoAwal += saldoAwal * bunga;
            bulan++;
            System.out.println("Saldo di bulan ke-" + bulan + ": Rp " + df.format(saldoAwal));
        }
    }
}

