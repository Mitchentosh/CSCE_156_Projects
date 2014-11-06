CSCE_156_Projects
=================

Projects for CSCE 156

package unl.cse.trucks;

public class TruckList {

    public void clear() {
    	throw new UnsupportedOperationException("Not yet implemented.");
    }

    public void addToStart(Truck t) {
    	//throw new UnsupportedOperationException("Not yet implemented.");
    	Driver newNode = new Driver(t, null);
    	size++;
        newNode.next = first;
        first = newNode;
    }

    public void addToEnd(Truck t) {
    	throw new UnsupportedOperationException("Not yet implemented.");
    }

    public void remove(int position) {
    	throw new UnsupportedOperationException("Not yet implemented.");
    }
    
    private TruckListNode getTruckListNode(int position) {
    	throw new UnsupportedOperationException("Not yet implemented.");
    }
    
    public Truck getTruck(int position) {
    	throw new UnsupportedOperationException("Not yet implemented.");    	
    }

    public void print() {
    	throw new UnsupportedOperationException("Not yet implemented.");
    }

}


