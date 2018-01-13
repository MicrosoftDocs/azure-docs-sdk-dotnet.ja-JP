<Type Name="AddStorageAccountParameters" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters">
  <TypeSignature Language="C#" Value="public class AddStorageAccountParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AddStorageAccountParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class AddStorageAccountParameters" />
  <TypeSignature Language="F#" Value="type AddStorageAccountParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="648b1-101">Data Lake Analytics アカウントに追加されているストレージ アカウントのストレージ アカウントのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="648b1-101">Storage account parameters for a storage account being added to a Data Lake Analytics account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AddStorageAccountParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="648b1-102">AddStorageAccountParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="648b1-102">Initializes a new instance of the AddStorageAccountParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AddStorageAccountParameters (string accessKey, string suffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accessKey, string suffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accessKey As String, Optional suffix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters : string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters (accessKey, suffix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accessKey" Type="System.String" />
        <Parameter Name="suffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accessKey"><span data-ttu-id="648b1-103">接続するために使用されるこの Azure ストレージ アカウントに関連付けられているアクセス キー。</span><span class="sxs-lookup"><span data-stu-id="648b1-103">the access key associated with this Azure Storage account that will be used to connect to it.</span></span></param>
        <param name="suffix"><span data-ttu-id="648b1-104">ストレージ アカウントの省略可能なサフィックス。</span><span class="sxs-lookup"><span data-stu-id="648b1-104">the optional suffix for the storage account.</span></span></param>
        <summary>
            <span data-ttu-id="648b1-105">AddStorageAccountParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="648b1-105">Initializes a new instance of the AddStorageAccountParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessKey">
      <MemberSignature Language="C#" Value="public string AccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters.AccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessKey As String" />
      <MemberSignature Language="F#" Value="member this.AccessKey : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters.AccessKey" />
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
            <span data-ttu-id="648b1-106">取得またはそれへの接続に使用されるこの Azure ストレージ アカウントに関連付けられているアクセス キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="648b1-106">Gets or sets the access key associated with this Azure Storage account that will be used to connect to it.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Suffix">
      <MemberSignature Language="C#" Value="public string Suffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Suffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters.Suffix" />
      <MemberSignature Language="VB.NET" Value="Public Property Suffix As String" />
      <MemberSignature Language="F#" Value="member this.Suffix : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters.Suffix" />
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
            <span data-ttu-id="648b1-107">取得またはストレージ アカウントの省略可能なサフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="648b1-107">Gets or sets the optional suffix for the storage account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="addStorageAccountParameters.Validate " />
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
            <span data-ttu-id="648b1-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="648b1-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="648b1-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="648b1-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>