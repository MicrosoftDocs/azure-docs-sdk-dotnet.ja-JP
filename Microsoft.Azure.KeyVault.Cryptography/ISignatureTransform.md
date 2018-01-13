<Type Name="ISignatureTransform" FullName="Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform">
  <TypeSignature Language="C#" Value="public interface ISignatureTransform" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISignatureTransform" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISignatureTransform" />
  <TypeSignature Language="F#" Value="type ISignatureTransform = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            署名変換を抽象化します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Sign">
      <MemberSignature Language="C#" Value="public byte[] Sign (byte[] digest);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] Sign(unsigned int8[] digest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform.Sign(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function Sign (digest As Byte()) As Byte()" />
      <MemberSignature Language="F#" Value="abstract member Sign : byte[] -&gt; byte[]" Usage="iSignatureTransform.Sign digest" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="digest" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="digest">メッセージ ダイジェストです。</param>
        <summary>
            指定されたダイジェスト値に署名します。
            </summary>
        <returns>署名の値。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Verify">
      <MemberSignature Language="C#" Value="public bool Verify (byte[] digest, byte[] signature);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Verify(unsigned int8[] digest, unsigned int8[] signature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform.Verify(System.Byte[],System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function Verify (digest As Byte(), signature As Byte()) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Verify : byte[] * byte[] -&gt; bool" Usage="iSignatureTransform.Verify (digest, signature)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="digest">メッセージ ダイジェストです。</param>
        <param name="signature">検証対象の署名。</param>
        <summary>
            指定されたシグネチャが指定されたメッセージ ダイジェストに対応していることを確認します。
            </summary>
        <returns>署名が有効な場合は true。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>