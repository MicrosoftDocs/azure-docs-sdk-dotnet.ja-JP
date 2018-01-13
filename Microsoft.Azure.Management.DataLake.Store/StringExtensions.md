<Type Name="StringExtensions" FullName="Microsoft.Azure.Management.DataLake.Store.StringExtensions">
  <TypeSignature Language="C#" Value="public static class StringExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StringExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.StringExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Class StringExtensions" />
  <TypeSignature Language="F#" Value="type StringExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FindNewline">
      <MemberSignature Language="C#" Value="public static int FindNewline (byte[] buffer, int startOffset, int length, bool reverse, System.Text.Encoding encoding, string delimiter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int32 FindNewline(unsigned int8[] buffer, int32 startOffset, int32 length, bool reverse, class System.Text.Encoding encoding, string delimiter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.StringExtensions.FindNewline(System.Byte[],System.Int32,System.Int32,System.Boolean,System.Text.Encoding,System.String)" />
      <MemberSignature Language="F#" Value="static member FindNewline : byte[] * int * int * bool * System.Text.Encoding * string -&gt; int" Usage="Microsoft.Azure.Management.DataLake.Store.StringExtensions.FindNewline (buffer, startOffset, length, reverse, encoding, delimiter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="System.Byte[]" />
        <Parameter Name="startOffset" Type="System.Int32" />
        <Parameter Name="length" Type="System.Int32" />
        <Parameter Name="reverse" Type="System.Boolean" />
        <Parameter Name="encoding" Type="System.Text.Encoding" />
        <Parameter Name="delimiter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="buffer">検索するバッファー。</param>
        <param name="startOffset">検索を開始する最初のバイトのインデックス。</param>
        <param name="length">検索は、バイト数特定 startOffset から開始します。</param>
        <param name="reverse">True の場合、バッファーの先頭まで startOffset から検索します。 False の場合、上方向に検索します。</param>
        <param name="encoding">To be added.</param>
        <param name="delimiter">To be added.</param>
        <summary>
            インデックスを検索、改行文字の指定したバッファーするか、最初のページまたは最後の (パラメーターに基づく)。
            結合の改行 (\r\n) の場合、返されるインデックスされている、シーケンスの最後の文字のです。
            </summary>
        <returns>最も近い改行文字 (の方向に基づく) ことが検出されたシーケンス内のインデックス。 見つからない場合は-1 を返します。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>