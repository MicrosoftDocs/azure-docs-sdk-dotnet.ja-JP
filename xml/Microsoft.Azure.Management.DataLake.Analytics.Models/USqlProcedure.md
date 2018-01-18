<Type Name="USqlProcedure" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure">
  <TypeSignature Language="C#" Value="public class USqlProcedure : Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlProcedure extends Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlProcedure&#xA;Inherits CatalogItem" />
  <TypeSignature Language="F#" Value="type USqlProcedure = class&#xA;    inherit CatalogItem" />
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
            <span data-ttu-id="740bb-101">Data Lake Analytics カタログ U-SQL プロシージャ項目。</span><span class="sxs-lookup"><span data-stu-id="740bb-101">A Data Lake Analytics catalog U-SQL procedure item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlProcedure ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="740bb-102">USqlProcedure クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="740bb-102">Initializes a new instance of the USqlProcedure class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlProcedure (string computeAccountName = null, Nullable&lt;Guid&gt; version = null, string databaseName = null, string schemaName = null, string name = null, string definition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computeAccountName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; version, string databaseName, string schemaName, string name, string definition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure.#ctor(System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional computeAccountName As String = null, Optional version As Nullable(Of Guid) = null, Optional databaseName As String = null, Optional schemaName As String = null, Optional name As String = null, Optional definition As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure : string * Nullable&lt;Guid&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure (computeAccountName, version, databaseName, schemaName, name, definition)" />
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
        <param name="computeAccountName"><span data-ttu-id="740bb-103">Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="740bb-103">the name of the Data Lake Analytics account.</span></span></param>
        <param name="version"><span data-ttu-id="740bb-104">カタログ アイテムのバージョン。</span><span class="sxs-lookup"><span data-stu-id="740bb-104">the version of the catalog item.</span></span></param>
        <param name="databaseName"><span data-ttu-id="740bb-105">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="740bb-105">the name of the database.</span></span></param>
        <param name="schemaName"><span data-ttu-id="740bb-106">この手順とデータベースに関連付けられているスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="740bb-106">the name of the schema associated with this procedure and database.</span></span></param>
        <param name="name"><span data-ttu-id="740bb-107">プロシージャの名前。</span><span class="sxs-lookup"><span data-stu-id="740bb-107">the name of the procedure.</span></span></param>
        <param name="definition"><span data-ttu-id="740bb-108">プロシージャの定義済みのクエリ。</span><span class="sxs-lookup"><span data-stu-id="740bb-108">the defined query of the procedure.</span></span></param>
        <summary>
            <span data-ttu-id="740bb-109">USqlProcedure クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="740bb-109">Initializes a new instance of the USqlProcedure class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure.DatabaseName" />
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
            <span data-ttu-id="740bb-110">取得またはデータベースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="740bb-110">Gets or sets the name of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Definition">
      <MemberSignature Language="C#" Value="public string Definition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Definition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure.Definition" />
      <MemberSignature Language="VB.NET" Value="Public Property Definition As String" />
      <MemberSignature Language="F#" Value="member this.Definition : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure.Definition" />
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
            <span data-ttu-id="740bb-111">取得またはプロシージャの定義済みのクエリを設定します。</span><span class="sxs-lookup"><span data-stu-id="740bb-111">Gets or sets the defined query of the procedure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="procName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="740bb-112">取得またはプロシージャの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="740bb-112">Gets or sets the name of the procedure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaName">
      <MemberSignature Language="C#" Value="public string SchemaName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchemaName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure.SchemaName" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaName As String" />
      <MemberSignature Language="F#" Value="member this.SchemaName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure.SchemaName" />
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
            <span data-ttu-id="740bb-113">取得または、この手順とデータベースに関連付けられているスキーマの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="740bb-113">Gets or sets the name of the schema associated with this procedure and database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>