    public double calculatetotals(double mealtotal) {
        double taxrate = 8.875;
        double mealtax = (mealtotal * taxrate) / 100;
        double finaltotal = mealtotal + mealtax;
        Decform.format(finaltotal);
        return finaltotal;      
    }
