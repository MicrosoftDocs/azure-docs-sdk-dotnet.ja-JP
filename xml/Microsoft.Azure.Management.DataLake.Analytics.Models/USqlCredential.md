<Type Name="USqlCredential" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential">
  <TypeSignature Language="C#" Value="public class USqlCredential : Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlCredential extends Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlCredential&#xA;Inherits CatalogItem" />
  <TypeSignature Language="F#" Value="type USqlCredential = class&#xA;    inherit CatalogItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3206f-101">Data Lake Analytics カタログ U SQL 資格情報項目。</span><span class="sxs-lookup"><span data-stu-id="3206f-101">A Data Lake Analytics catalog U-SQL credential item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3206f-102">USqlCredential クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3206f-102">Initializes a new instance of the USqlCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlCredential (string computeAccountName = null, Nullable&lt;Guid&gt; version = null, string name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computeAccountName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; version, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential.#ctor(System.String,System.Nullable{System.Guid},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional computeAccountName As String = null, Optional version As Nullable(Of Guid) = null, Optional name As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential : string * Nullable&lt;Guid&gt; * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential (computeAccountName, version, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="computeAccountName" Type="System.String" />
        <Parameter Name="version" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="computeAccountName"><span data-ttu-id="3206f-103">Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="3206f-103">the name of the Data Lake Analytics account.</span></span></param>
        <param name="version"><span data-ttu-id="3206f-104">カタログ アイテムのバージョン。</span><span class="sxs-lookup"><span data-stu-id="3206f-104">the version of the catalog item.</span></span></param>
        <param name="name"><span data-ttu-id="3206f-105">資格情報の名前です。</span><span class="sxs-lookup"><span data-stu-id="3206f-105">the name of the credential.</span></span></param>
        <summary>
            <span data-ttu-id="3206f-106">USqlCredential クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3206f-106">Initializes a new instance of the USqlCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="credentialName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3206f-107">取得または資格情報の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="3206f-107">Gets or sets the name of the credential.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>