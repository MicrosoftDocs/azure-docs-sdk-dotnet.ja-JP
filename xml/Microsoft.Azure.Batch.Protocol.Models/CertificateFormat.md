<Type Name="CertificateFormat" FullName="Microsoft.Azure.Batch.Protocol.Models.CertificateFormat">
  <TypeSignature Language="C#" Value="public enum CertificateFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed CertificateFormat extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.CertificateFormat" />
  <TypeSignature Language="VB.NET" Value="Public Enum CertificateFormat" />
  <TypeSignature Language="F#" Value="type CertificateFormat = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="1c61e-101">CertificateFormat の値を定義します。</span><span class="sxs-lookup"><span data-stu-id="1c61e-101">Defines values for CertificateFormat.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Cer">
      <MemberSignature Language="C#" Value="Cer" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateFormat Cer = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.CertificateFormat.Cer" />
      <MemberSignature Language="VB.NET" Value="Cer" />
      <MemberSignature Language="F#" Value="Cer = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateFormat.Cer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="cer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateFormat</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c61e-102">証明書は、base64 でエンコードされた X.509 証明書です。</span><span class="sxs-lookup"><span data-stu-id="1c61e-102">The certificate is a base64-encoded X.509 certificate.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Pfx">
      <MemberSignature Language="C#" Value="Pfx" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateFormat Pfx = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.CertificateFormat.Pfx" />
      <MemberSignature Language="VB.NET" Value="Pfx" />
      <MemberSignature Language="F#" Value="Pfx = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateFormat.Pfx" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="pfx")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateFormat</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c61e-103">証明書は PFX (PKCS #12) 形式の証明書または証明書チェーンがします。</span><span class="sxs-lookup"><span data-stu-id="1c61e-103">The certificate is a PFX (PKCS#12) formatted certificate or certificate chain.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>