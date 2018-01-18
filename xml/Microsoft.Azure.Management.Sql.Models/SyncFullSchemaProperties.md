<Type Name="SyncFullSchemaProperties" FullName="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties">
  <TypeSignature Language="C#" Value="public class SyncFullSchemaProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncFullSchemaProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncFullSchemaProperties" />
  <TypeSignature Language="F#" Value="type SyncFullSchemaProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ea516-101">データベースの完全スキーマのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="ea516-101">Properties of the database full schema.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncFullSchemaProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ea516-102">SyncFullSchemaProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ea516-102">Initializes a new instance of the SyncFullSchemaProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncFullSchemaProperties (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable&gt; tables = null, Nullable&lt;DateTime&gt; lastUpdateTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable&gt; tables, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastUpdateTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional tables As IList(Of SyncFullSchemaTable) = null, Optional lastUpdateTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties" Usage="new Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties (tables, lastUpdateTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tables" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable&gt;" />
        <Parameter Name="lastUpdateTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="tables"><span data-ttu-id="ea516-103">データベースの完全スキーマ内のテーブルの一覧です。</span><span class="sxs-lookup"><span data-stu-id="ea516-103">List of tables in the database full schema.</span></span></param>
        <param name="lastUpdateTime"><span data-ttu-id="ea516-104">データベース スキーマの時間の最終更新します。</span><span class="sxs-lookup"><span data-stu-id="ea516-104">Last update time of the database schema.</span></span></param>
        <summary>
            <span data-ttu-id="ea516-105">SyncFullSchemaProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ea516-105">Initializes a new instance of the SyncFullSchemaProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastUpdateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastUpdateTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties.LastUpdateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastUpdateTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea516-106">取得の最終更新データベース スキーマの時間。</span><span class="sxs-lookup"><span data-stu-id="ea516-106">Gets last update time of the database schema.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tables">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable&gt; Tables { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable&gt; Tables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties.Tables" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tables As IList(Of SyncFullSchemaTable)" />
      <MemberSignature Language="F#" Value="member this.Tables : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties.Tables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tables")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea516-107">データベースの完全スキーマ内のテーブルの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea516-107">Gets list of tables in the database full schema.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>