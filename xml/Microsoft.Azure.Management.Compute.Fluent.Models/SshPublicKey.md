<Type Name="SshPublicKey" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey">
  <TypeSignature Language="C#" Value="public class SshPublicKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SshPublicKey extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey" />
  <TypeSignature Language="VB.NET" Value="Public Class SshPublicKey" />
  <TypeSignature Language="F#" Value="type SshPublicKey = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="24dab-101">公開キーが配置されている Linux VM 上の SSH 証明書の公開キーとパスに関する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="24dab-101">Contains information about SSH certificate public key and the path on the Linux VM where the public key is placed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SshPublicKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="24dab-102">SshPublicKey クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="24dab-102">Initializes a new instance of the SshPublicKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SshPublicKey (string path = null, string keyData = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string path, string keyData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional path As String = null, Optional keyData As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey : string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey (path, keyData)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="keyData" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="24dab-103">SSH 公開キーが格納されている作成した VM を完全なパスを指定します。</span><span class="sxs-lookup"><span data-stu-id="24dab-103">Specifies the full path on the created VM where SSH public key is stored.</span></span> <span data-ttu-id="24dab-104">ファイルが既に存在する場合は、ファイルに指定したキーが追加されます。</span><span class="sxs-lookup"><span data-stu-id="24dab-104">If the file already exists, the specified key is appended to the file.</span></span></param>
        <param name="keyData"><span data-ttu-id="24dab-105">証明書の公開キーが SSH を介した VM への認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="24dab-105">Certificate public key used to authenticate to the VM through SSH.</span></span> <span data-ttu-id="24dab-106">証明書は、ヘッダーの有無 Pem 形式である必要があります。</span><span class="sxs-lookup"><span data-stu-id="24dab-106">The certificate must be in Pem format with or without headers.</span></span></param>
        <summary>
            <span data-ttu-id="24dab-107">SshPublicKey クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="24dab-107">Initializes a new instance of the SshPublicKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyData">
      <MemberSignature Language="C#" Value="public string KeyData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey.KeyData" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyData As String" />
      <MemberSignature Language="F#" Value="member this.KeyData : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey.KeyData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24dab-108">取得または SSH を介した VM への認証に使用される証明書の公開キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="24dab-108">Gets or sets certificate public key used to authenticate to the VM through SSH.</span></span> <span data-ttu-id="24dab-109">証明書は、ヘッダーの有無 Pem 形式である必要があります。</span><span class="sxs-lookup"><span data-stu-id="24dab-109">The certificate must be in Pem format with or without headers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.SshPublicKey.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="24dab-110">取得または設定は、SSH 公開キーが格納されている作成した VM 上の完全パスを指定します。</span><span class="sxs-lookup"><span data-stu-id="24dab-110">Gets or sets specifies the full path on the created VM where SSH public key is stored.</span></span> <span data-ttu-id="24dab-111">ファイルが既に存在する場合は、ファイルに指定したキーが追加されます。</span><span class="sxs-lookup"><span data-stu-id="24dab-111">If the file already exists, the specified key is appended to the file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>