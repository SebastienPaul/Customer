# Cellphone

public class CellPhone {
	String model, manufacturer;
	private int monthsOfWarranty;
	private float price;

	public CellPhone(String mo, String ma, int MoW, float p){
		model = mo;
		manufacturer = ma;
		monthsOfWarranty = MoW;
		price = p;
	}
	public String getModel(){return model;}
	public String getManufacturer(){return manufacturer;}
	public int getMonthsOfWarranty(){return monthsOfWarranty;}
	public float getPrice(){return price;}
}

