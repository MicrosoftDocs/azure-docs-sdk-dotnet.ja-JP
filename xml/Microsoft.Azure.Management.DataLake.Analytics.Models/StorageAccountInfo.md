<Type Name="StorageAccountInfo" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo">
  <TypeSignature Language="C#" Value="public class StorageAccountInfo : Microsoft.Azure.Management.DataLake.Analytics.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountInfo extends Microsoft.Azure.Management.DataLake.Analytics.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountInfo&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type StorageAccountInfo = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="52e94-101">Azure ストレージ アカウントの情報です。</span><span class="sxs-lookup"><span data-stu-id="52e94-101">Azure Storage account information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="52e94-102">StorageAccountInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="52e94-102">Initializes a new instance of the StorageAccountInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountInfo (string name, string accessKey, string id = null, string type = null, string suffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string accessKey, string id, string type, string suffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, accessKey As String, Optional id As String = null, Optional type As String = null, Optional suffix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo : string * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo (name, accessKey, id, type, suffix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="accessKey" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="suffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="52e94-103">リソース名</span><span class="sxs-lookup"><span data-stu-id="52e94-103">Resource name</span></span></param>
        <param name="accessKey"><span data-ttu-id="52e94-104">接続するために使用されるこの Azure ストレージ アカウントに関連付けられているアクセス キー。</span><span class="sxs-lookup"><span data-stu-id="52e94-104">the access key associated with this Azure Storage account that will be used to connect to it.</span></span></param>
        <param name="id"><span data-ttu-id="52e94-105">リソース Id</span><span class="sxs-lookup"><span data-stu-id="52e94-105">Resource Id</span></span></param>
        <param name="type"><span data-ttu-id="52e94-106">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="52e94-106">Resource type</span></span></param>
        <param name="suffix"><span data-ttu-id="52e94-107">ストレージ アカウントの省略可能なサフィックス。</span><span class="sxs-lookup"><span data-stu-id="52e94-107">the optional suffix for the storage account.</span></span></param>
        <summary>
            <span data-ttu-id="52e94-108">StorageAccountInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="52e94-108">Initializes a new instance of the StorageAccountInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessKey">
      <MemberSignature Language="C#" Value="public string AccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo.AccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessKey As String" />
      <MemberSignature Language="F#" Value="member this.AccessKey : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo.AccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52e94-109">取得またはそれへの接続に使用されるこの Azure ストレージ アカウントに関連付けられているアクセス キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="52e94-109">Gets or sets the access key associated with this Azure Storage account that will be used to connect to it.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Suffix">
      <MemberSignature Language="C#" Value="public string Suffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Suffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo.Suffix" />
      <MemberSignature Language="VB.NET" Value="Public Property Suffix As String" />
      <MemberSignature Language="F#" Value="member this.Suffix : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo.Suffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.suffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52e94-110">取得またはストレージ アカウントの省略可能なサフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="52e94-110">Gets or sets the optional suffix for the storage account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="storageAccountInfo.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="52e94-111">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="52e94-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="52e94-112">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="52e94-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>