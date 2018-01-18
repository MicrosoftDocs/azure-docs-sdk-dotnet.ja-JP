<Type Name="DataSourceListResult" FullName="Microsoft.Azure.Search.Models.DataSourceListResult">
  <TypeSignature Language="C#" Value="public class DataSourceListResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataSourceListResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DataSourceListResult" />
  <TypeSignature Language="VB.NET" Value="Public Class DataSourceListResult" />
  <TypeSignature Language="F#" Value="type DataSourceListResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7af90-101">データソースの一覧表示要求から応答します。</span><span class="sxs-lookup"><span data-stu-id="7af90-101">Response from a List Datasources request.</span></span> <span data-ttu-id="7af90-102">成功した場合は、すべてのデータ ソースの完全定義が含まれます。</span><span class="sxs-lookup"><span data-stu-id="7af90-102">If successful, it includes the full definitions of all datasources.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSourceListResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSourceListResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7af90-103">DataSourceListResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7af90-103">Initializes a new instance of the DataSourceListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSourceListResult (System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.DataSource&gt; dataSources = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.DataSource&gt; dataSources) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSourceListResult.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Search.Models.DataSource})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dataSources As IList(Of DataSource) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.DataSourceListResult : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.DataSource&gt; -&gt; Microsoft.Azure.Search.Models.DataSourceListResult" Usage="new Microsoft.Azure.Search.Models.DataSourceListResult dataSources" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataSources" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.DataSource&gt;" />
      </Parameters>
      <Docs>
        <param name="dataSources"><span data-ttu-id="7af90-104">Search サービスでデータ ソース。</span><span class="sxs-lookup"><span data-stu-id="7af90-104">The datasources in the Search service.</span></span></param>
        <summary>
            <span data-ttu-id="7af90-105">DataSourceListResult クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7af90-105">Initializes a new instance of the DataSourceListResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSources">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.DataSource&gt; DataSources { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.DataSource&gt; DataSources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSourceListResult.DataSources" />
      <MemberSignature Language="VB.NET" Value="Public Property DataSources As IList(Of DataSource)" />
      <MemberSignature Language="F#" Value="member this.DataSources : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.DataSource&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DataSourceListResult.DataSources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7af90-106">Search サービスで、データ ソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="7af90-106">Gets the datasources in the Search service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>