    public double calculatetotals(double mealtotal) {
        double mealtax = (mealtotal * 8.875) / 100;
        double finaltotal = mealtotal + mealtax;
        Decform.format(finaltotal);
        return finaltotal;      
    }
