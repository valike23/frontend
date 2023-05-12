<script lang="ts">
    const submit =() =>{

    }
</script>

<section class="ds s-py-60 s-py-md-90 c-mb-20 c-gutter-20 form-section">
    <div class="container">
        <div class="row">
            <div class="divider-70 d-none d-xl-block"></div>
            <div class="col-12">
                <h3 class="special-heading text-center">GET IN TOUCH</h3>
                <div class="divider-60 d-none d-xl-block"></div>
                <div class="divider-40 hidden-above-md"></div>
                <form on:submit|preventDefault={submit}>
                    <div class="row">
                        <div class="col-xs-12 col-md-4">
                            <div class="form-group">
                                <input class="form-control" type="text" name="text_1fcfb46" placeholder="Full Name"  required>
                            </div>
                        </div>
                        <div class="col-xs-12 col-md-4">
                            <div class="form-group">
                                <input class="form-control" type="text" name="text_42598d5" placeholder="Phone Number"  required>
                            </div>
                        </div>
                        <div class="col-xs-12 col-md-2">
                            <div class="form-group">
                                <div class="field-date">
                                    <select class="form-control" name="date_time_42a77ed" required>
                                        <option value>Date</option>
                                        <option value="Date">Date</option>
                                        <option value="Date">Date</option>
                                    </select>
                                </div>
                            </div>
                        </div>
                        <div class="col-xs-12 col-md-2">
                            <div class="form-group">
                                <div class="field-date">
                                    <select class="form-control" name="date_time_b63914d" required>
                                        <option value>Time</option>
                                        <option value="Time">Time</option>
                                        <option value="Time">Time</option>
                                    </select>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-12">
                            <div class="form-group">
                                <textarea class="form-control" rows="5" name="textarea_edfe99b" placeholder="Your Message" required></textarea>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-12 text-center">
                            <button class="btn btn-outline-maincolor" type="submit">our contacts</button>
                        </div>
                    </div>
                </form>
            </div>
            <div class="divider-40 d-none d-xl-block"></div>
        </div>
    </div>
</section>