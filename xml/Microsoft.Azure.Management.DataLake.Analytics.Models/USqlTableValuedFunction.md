<Type Name="USqlTableValuedFunction" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction">
  <TypeSignature Language="C#" Value="public class USqlTableValuedFunction : Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlTableValuedFunction extends Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlTableValuedFunction&#xA;Inherits CatalogItem" />
  <TypeSignature Language="F#" Value="type USqlTableValuedFunction = class&#xA;    inherit CatalogItem" />
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
            <span data-ttu-id="af953-101">Data Lake Analytics カタログ U SQL テーブル値関数アイテムです。</span><span class="sxs-lookup"><span data-stu-id="af953-101">A Data Lake Analytics catalog U-SQL table valued function item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlTableValuedFunction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="af953-102">USqlTableValuedFunction クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="af953-102">Initializes a new instance of the USqlTableValuedFunction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlTableValuedFunction (string computeAccountName = null, Nullable&lt;Guid&gt; version = null, string databaseName = null, string schemaName = null, string name = null, string definition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computeAccountName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; version, string databaseName, string schemaName, string name, string definition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.#ctor(System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional computeAccountName As String = null, Optional version As Nullable(Of Guid) = null, Optional databaseName As String = null, Optional schemaName As String = null, Optional name As String = null, Optional definition As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction : string * Nullable&lt;Guid&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction (computeAccountName, version, databaseName, schemaName, name, definition)" />
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
        <param name="computeAccountName"><span data-ttu-id="af953-103">Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="af953-103">the name of the Data Lake Analytics account.</span></span></param>
        <param name="version"><span data-ttu-id="af953-104">カタログ アイテムのバージョン。</span><span class="sxs-lookup"><span data-stu-id="af953-104">the version of the catalog item.</span></span></param>
        <param name="databaseName"><span data-ttu-id="af953-105">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="af953-105">the name of the database.</span></span></param>
        <param name="schemaName"><span data-ttu-id="af953-106">このデータベースに関連付けられているスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="af953-106">the name of the schema associated with this database.</span></span></param>
        <param name="name"><span data-ttu-id="af953-107">テーブル値関数の名前。</span><span class="sxs-lookup"><span data-stu-id="af953-107">the name of the table valued function.</span></span></param>
        <param name="definition"><span data-ttu-id="af953-108">テーブル値関数の定義。</span><span class="sxs-lookup"><span data-stu-id="af953-108">the definition of the table valued function.</span></span></param>
        <summary>
            <span data-ttu-id="af953-109">USqlTableValuedFunction クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="af953-109">Initializes a new instance of the USqlTableValuedFunction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.DatabaseName" />
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
            <span data-ttu-id="af953-110">取得またはデータベースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="af953-110">Gets or sets the name of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Definition">
      <MemberSignature Language="C#" Value="public string Definition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Definition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.Definition" />
      <MemberSignature Language="VB.NET" Value="Public Property Definition As String" />
      <MemberSignature Language="F#" Value="member this.Definition : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.Definition" />
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
            <span data-ttu-id="af953-111">取得またはテーブル値関数の定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="af953-111">Gets or sets the definition of the table valued function.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tvfName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="af953-112">取得またはテーブル値関数の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="af953-112">Gets or sets the name of the table valued function.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaName">
      <MemberSignature Language="C#" Value="public string SchemaName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchemaName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.SchemaName" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaName As String" />
      <MemberSignature Language="F#" Value="member this.SchemaName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.SchemaName" />
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
            <span data-ttu-id="af953-113">取得またはこのデータベースに関連付けられているスキーマの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="af953-113">Gets or sets the name of the schema associated with this database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>