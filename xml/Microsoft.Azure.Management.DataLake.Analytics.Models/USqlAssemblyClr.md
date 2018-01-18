<Type Name="USqlAssemblyClr" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr">
  <TypeSignature Language="C#" Value="public class USqlAssemblyClr : Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlAssemblyClr extends Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlAssemblyClr&#xA;Inherits CatalogItem" />
  <TypeSignature Language="F#" Value="type USqlAssemblyClr = class&#xA;    inherit CatalogItem" />
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
            <span data-ttu-id="db9d4-101">Data Lake Analytics カタログ U-SQL アセンブリ CLR アイテムです。</span><span class="sxs-lookup"><span data-stu-id="db9d4-101">A Data Lake Analytics catalog U-SQL assembly CLR item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlAssemblyClr ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="db9d4-102">USqlAssemblyClr クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="db9d4-102">Initializes a new instance of the USqlAssemblyClr class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlAssemblyClr (string computeAccountName = null, Nullable&lt;Guid&gt; version = null, string databaseName = null, string name = null, string clrName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computeAccountName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; version, string databaseName, string name, string clrName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr.#ctor(System.String,System.Nullable{System.Guid},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional computeAccountName As String = null, Optional version As Nullable(Of Guid) = null, Optional databaseName As String = null, Optional name As String = null, Optional clrName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr : string * Nullable&lt;Guid&gt; * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr (computeAccountName, version, databaseName, name, clrName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="computeAccountName" Type="System.String" />
        <Parameter Name="version" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="clrName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="computeAccountName"><span data-ttu-id="db9d4-103">Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="db9d4-103">the name of the Data Lake Analytics account.</span></span></param>
        <param name="version"><span data-ttu-id="db9d4-104">カタログ アイテムのバージョン。</span><span class="sxs-lookup"><span data-stu-id="db9d4-104">the version of the catalog item.</span></span></param>
        <param name="databaseName"><span data-ttu-id="db9d4-105">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="db9d4-105">the name of the database.</span></span></param>
        <param name="name"><span data-ttu-id="db9d4-106">アセンブリの名前。</span><span class="sxs-lookup"><span data-stu-id="db9d4-106">the name of the assembly.</span></span></param>
        <param name="clrName"><span data-ttu-id="db9d4-107">CLR の名前。</span><span class="sxs-lookup"><span data-stu-id="db9d4-107">the name of the CLR.</span></span></param>
        <summary>
            <span data-ttu-id="db9d4-108">USqlAssemblyClr クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="db9d4-108">Initializes a new instance of the USqlAssemblyClr class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClrName">
      <MemberSignature Language="C#" Value="public string ClrName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClrName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr.ClrName" />
      <MemberSignature Language="VB.NET" Value="Public Property ClrName As String" />
      <MemberSignature Language="F#" Value="member this.ClrName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr.ClrName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="clrName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="db9d4-109">取得または CLR の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="db9d4-109">Gets or sets the name of the CLR.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr.DatabaseName" />
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
            <span data-ttu-id="db9d4-110">取得またはデータベースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="db9d4-110">Gets or sets the name of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="assemblyClrName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="db9d4-111">アセンブリの名前を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="db9d4-111">Gets or sets the name of the assembly.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>