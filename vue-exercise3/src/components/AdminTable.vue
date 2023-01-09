<template>
    <div class="col-12 col-md-10 mt-5 T-table">
        <table class="table table-striped table-dark">
            <thead>
                <tr>
                    <th>ItemNo.</th>
                    <th>Item</th>
                    <th>Price</th>
                    <th>Qty</th>
                    <th>Total</th>
                    <th>Purchase</th>
                    <th>Delete</th>
                </tr>
            </thead>
            <tbody class="checkout-list">
                <tr>
                    <td>1001</td>
                    <td>Horizon</td>
                    <td>500</td>
                    <td>3</td>
                    <td>R1500</td>
                    <td>
                        <a href="#" class="btn btn-info btn-sm edit">Add</a>
                    </td>
                    <td>
                        <a href="#" class="btn btn-danger btn-sm edit">Delete</a>
                    </td>
                </tr>
            </tbody>
        </table>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
.T-table{
    margin: auto;
    display: flex;
    align-content: center;
    justify-content: center;
}
</style>