<Type Name="USqlPackage" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage">
  <TypeSignature Language="C#" Value="public class USqlPackage : Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlPackage extends Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlPackage&#xA;Inherits CatalogItem" />
  <TypeSignature Language="F#" Value="type USqlPackage = class&#xA;    inherit CatalogItem" />
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
            <span data-ttu-id="bfecd-101">Data Lake Analytics カタログ U-SQL パッケージ項目。</span><span class="sxs-lookup"><span data-stu-id="bfecd-101">A Data Lake Analytics catalog U-SQL package item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlPackage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bfecd-102">USqlPackage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bfecd-102">Initializes a new instance of the USqlPackage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlPackage (string computeAccountName = null, Nullable&lt;Guid&gt; version = null, string databaseName = null, string schemaName = null, string name = null, string definition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computeAccountName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; version, string databaseName, string schemaName, string name, string definition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.#ctor(System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional computeAccountName As String = null, Optional version As Nullable(Of Guid) = null, Optional databaseName As String = null, Optional schemaName As String = null, Optional name As String = null, Optional definition As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage : string * Nullable&lt;Guid&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage (computeAccountName, version, databaseName, schemaName, name, definition)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="computeAccountName" Type="System.String" />
        <Parameter Name="version" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="definition" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="computeAccountName"><span data-ttu-id="bfecd-103">Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="bfecd-103">the name of the Data Lake Analytics account.</span></span></param>
        <param name="version"><span data-ttu-id="bfecd-104">カタログ アイテムのバージョン。</span><span class="sxs-lookup"><span data-stu-id="bfecd-104">the version of the catalog item.</span></span></param>
        <param name="databaseName"><span data-ttu-id="bfecd-105">パッケージを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="bfecd-105">the name of the database containing the package.</span></span></param>
        <param name="schemaName"><span data-ttu-id="bfecd-106">このパッケージとデータベースに関連付けられているスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="bfecd-106">the name of the schema associated with this package and database.</span></span></param>
        <param name="name"><span data-ttu-id="bfecd-107">パッケージの名前。</span><span class="sxs-lookup"><span data-stu-id="bfecd-107">the name of the package.</span></span></param>
        <param name="definition"><span data-ttu-id="bfecd-108">パッケージの定義。</span><span class="sxs-lookup"><span data-stu-id="bfecd-108">the definition of the package.</span></span></param>
        <summary>
            <span data-ttu-id="bfecd-109">USqlPackage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bfecd-109">Initializes a new instance of the USqlPackage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="databaseName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfecd-110">取得またはパッケージを含むデータベースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="bfecd-110">Gets or sets the name of the database containing the package.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Definition">
      <MemberSignature Language="C#" Value="public string Definition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Definition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.Definition" />
      <MemberSignature Language="VB.NET" Value="Public Property Definition As String" />
      <MemberSignature Language="F#" Value="member this.Definition : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.Definition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="definition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfecd-111">取得またはパッケージの定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="bfecd-111">Gets or sets the definition of the package.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="packageName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfecd-112">取得またはパッケージの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="bfecd-112">Gets or sets the name of the package.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaName">
      <MemberSignature Language="C#" Value="public string SchemaName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchemaName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.SchemaName" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaName As String" />
      <MemberSignature Language="F#" Value="member this.SchemaName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.SchemaName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schemaName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfecd-113">取得またはこのパッケージとデータベースに関連付けられているスキーマの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="bfecd-113">Gets or sets the name of the schema associated with this package and database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>