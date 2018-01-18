<Type Name="ExternalTable" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable">
  <TypeSignature Language="C#" Value="public class ExternalTable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExternalTable extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable" />
  <TypeSignature Language="VB.NET" Value="Public Class ExternalTable" />
  <TypeSignature Language="F#" Value="type ExternalTable = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3887d-101">Data Lake Analytics カタログ テーブルの外部項目。</span><span class="sxs-lookup"><span data-stu-id="3887d-101">A Data Lake Analytics catalog external table item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExternalTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3887d-102">ExternalTable クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3887d-102">Initializes a new instance of the ExternalTable class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExternalTable (string tableName = null, Microsoft.Azure.Management.DataLake.Analytics.Models.EntityId dataSource = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tableName, class Microsoft.Azure.Management.DataLake.Analytics.Models.EntityId dataSource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable.#ctor(System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.EntityId)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional tableName As String = null, Optional dataSource As EntityId = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable : string * Microsoft.Azure.Management.DataLake.Analytics.Models.EntityId -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable (tableName, dataSource)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.EntityId" />
      </Parameters>
      <Docs>
        <param name="tableName"><span data-ttu-id="3887d-103">このデータベースとスキーマに関連付けられているテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="3887d-103">the name of the table associated with this database and schema.</span></span></param>
        <param name="dataSource"><span data-ttu-id="3887d-104">この外部テーブルに関連付けられているデータ ソース。</span><span class="sxs-lookup"><span data-stu-id="3887d-104">the data source associated with this external table.</span></span></param>
        <summary>
            <span data-ttu-id="3887d-105">ExternalTable クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3887d-105">Initializes a new instance of the ExternalTable class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.EntityId DataSource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.EntityId DataSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable.DataSource" />
      <MemberSignature Language="VB.NET" Value="Public Property DataSource As EntityId" />
      <MemberSignature Language="F#" Value="member this.DataSource : Microsoft.Azure.Management.DataLake.Analytics.Models.EntityId with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable.DataSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataSource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.EntityId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3887d-106">取得またはこの外部テーブルに関連付けられているデータ ソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="3887d-106">Gets or sets the data source associated with this external table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableName">
      <MemberSignature Language="C#" Value="public string TableName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TableName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable.TableName" />
      <MemberSignature Language="VB.NET" Value="Public Property TableName As String" />
      <MemberSignature Language="F#" Value="member this.TableName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable.TableName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tableName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3887d-107">取得またはこのデータベースとスキーマに関連付けられているテーブルの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="3887d-107">Gets or sets the name of the table associated with this database and schema.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>