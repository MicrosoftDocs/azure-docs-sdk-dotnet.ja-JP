<Type Name="ReferenceTableInfo" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo">
  <TypeSignature Language="C#" Value="public class ReferenceTableInfo : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.TableInfo, IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit ReferenceTableInfo extends Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.TableInfo implements class System.IEquatable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ReferenceTableInfo&#xA;Inherits TableInfo&#xA;Implements IEquatable(Of ReferenceTableInfo)" />
  <TypeSignature Language="F#" Value="type ReferenceTableInfo = class&#xA;    inherit TableInfo&#xA;    interface IEquatable&lt;ReferenceTableInfo&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.TableInfo</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="ReferenceTableInfo", Namespace="")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="476ef-101">1 つの参照テーブルに関する情報を表します。</span><span class="sxs-lookup"><span data-stu-id="476ef-101">Represents information about a single reference table.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReferenceTableInfo (string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo tableName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName"><span data-ttu-id="476ef-102">参照テーブル名です。</span><span class="sxs-lookup"><span data-stu-id="476ef-102">Reference table name.</span></span></param>
        <summary>
            <span data-ttu-id="476ef-103"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="476ef-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReferenceTableInfo (string schemaName, string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string schemaName, string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (schemaName As String, tableName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo : string * string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo (schemaName, tableName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="schemaName"><span data-ttu-id="476ef-104">参照テーブルのスキーマ名です。</span><span class="sxs-lookup"><span data-stu-id="476ef-104">Schema name of the reference table.</span></span></param>
        <param name="tableName"><span data-ttu-id="476ef-105">参照テーブル名です。</span><span class="sxs-lookup"><span data-stu-id="476ef-105">Reference table name.</span></span></param>
        <summary>
            <span data-ttu-id="476ef-106"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="476ef-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo.Equals(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As ReferenceTableInfo) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo -&gt; bool" Usage="referenceTableInfo.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="476ef-107">現在のオブジェクトと比較する ReferenceTableInfo オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="476ef-107">The ReferenceTableInfo object to compare with the current object.</span></span></param>
        <summary>
            <span data-ttu-id="476ef-108">指定した ReferenceTableInfo オブジェクトが現在のオブジェクトと等しいかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="476ef-108">Determines whether the specified ReferenceTableInfo object is equal to the current object.</span></span>
            </summary>
        <returns><span data-ttu-id="476ef-109">指定した ReferenceTableInfo オブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="476ef-109">true if the specified ReferenceTableInfo object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="referenceTableInfo.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="476ef-110">現在の ReferenceTableInfo オブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="476ef-110">The object to compare with the current ReferenceTableInfo object.</span></span></param>
        <summary>
            <span data-ttu-id="476ef-111">オブジェクト クラスの Equals() メソッドをオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="476ef-111">Overrides the Equals() method of Object class.</span></span> <span data-ttu-id="476ef-112">指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="476ef-112">Determines whether the specified object is equal to the current object.</span></span>
            </summary>
        <returns><span data-ttu-id="476ef-113">指定したオブジェクトが現在の ReferenceTableInfo オブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="476ef-113">true if the specified object is equal to the current ReferenceTableInfo object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="referenceTableInfo.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="476ef-114">このインスタンスのハッシュ コードを計算します。</span><span class="sxs-lookup"><span data-stu-id="476ef-114">Calculates the hash code for this instance.</span></span>
            </summary>
        <returns><span data-ttu-id="476ef-115">オブジェクトのハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="476ef-115">Hash code for the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>