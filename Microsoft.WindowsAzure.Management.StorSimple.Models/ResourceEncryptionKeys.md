<Type Name="ResourceEncryptionKeys" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.ResourceEncryptionKeys">
  <TypeSignature Language="C#" Value="public class ResourceEncryptionKeys" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceEncryptionKeys extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.ResourceEncryptionKeys" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceEncryptionKeys" />
  <TypeSignature Language="F#" Value="type ResourceEncryptionKeys = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            リソースの暗号化キーを含むオブジェクトを表す
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceEncryptionKeys ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.ResourceEncryptionKeys.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ResourceEncryptionKeys クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceEncryptionKeys (string encodedEncryptedPublicKey, string thumbprint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string encodedEncryptedPublicKey, string thumbprint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.ResourceEncryptionKeys.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (encodedEncryptedPublicKey As String, thumbprint As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.Models.ResourceEncryptionKeys : string * string -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.ResourceEncryptionKeys" Usage="new Microsoft.WindowsAzure.Management.StorSimple.Models.ResourceEncryptionKeys (encodedEncryptedPublicKey, thumbprint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="encodedEncryptedPublicKey" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="encodedEncryptedPublicKey">To be added.</param>
        <param name="thumbprint">To be added.</param>
        <summary>
            必須の引数で ResourceEncryptionKeys クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncodedEncryptedPublicKey">
      <MemberSignature Language="C#" Value="public string EncodedEncryptedPublicKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncodedEncryptedPublicKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.ResourceEncryptionKeys.EncodedEncryptedPublicKey" />
      <MemberSignature Language="VB.NET" Value="Public Property EncodedEncryptedPublicKey As String" />
      <MemberSignature Language="F#" Value="member this.EncodedEncryptedPublicKey : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.ResourceEncryptionKeys.EncodedEncryptedPublicKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 チャネルの整合性キーで暗号化されたパブリック キー
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceName">
      <MemberSignature Language="C#" Value="public string ResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.ResourceEncryptionKeys.ResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceName As String" />
      <MemberSignature Language="F#" Value="member this.ResourceName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.ResourceEncryptionKeys.ResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 エンコードされたキーが所属するリソースの名前
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.ResourceEncryptionKeys.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.ResourceEncryptionKeys.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 チャネルの整合性キーで暗号化されたパブリック キー
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>