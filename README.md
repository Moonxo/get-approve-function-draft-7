# get-approve-function-draft-7
  function getApprovedRecords()
        external
        pure
        override
        returns (string[] memory)
    {
        string[] memory approved = new string[](9);
        approved[0] = "Thriller";
        approved[1] = "Billy Jean";
        approved[2] = "Twilight";
        approved[3] = "Dancing in the Mooonlight";
        approved[4] = "In the Night";
        approved[5] = "Rocket Man";
        return approved;
