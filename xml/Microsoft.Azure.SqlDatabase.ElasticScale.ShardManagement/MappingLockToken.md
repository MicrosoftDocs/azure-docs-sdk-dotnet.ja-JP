<Type Name="MappingLockToken" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken">
  <TypeSignature Language="C#" Value="public sealed class MappingLockToken : IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MappingLockToken extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MappingLockToken&#xA;Implements IEquatable(Of MappingLockToken)" />
  <TypeSignature Language="F#" Value="type MappingLockToken = class&#xA;    interface IEquatable&lt;MappingLockToken&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="MappingLockToken", Namespace="")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="8a78b-101">マッピングで、ロックの所有者を表すパブリック型が保持されています。</span><span class="sxs-lookup"><span data-stu-id="8a78b-101">Public type that represents the owner of a lock held on a mapping</span></span>
            </summary>
    <remarks><span data-ttu-id="8a78b-102">このクラスは変更できません。</span><span class="sxs-lookup"><span data-stu-id="8a78b-102">This class is immutable</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As MappingLockToken" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8a78b-103"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="8a78b-103">Creates an instance of <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /></span></span></summary>
        <returns><span data-ttu-id="8a78b-104"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="8a78b-104">An instance of <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /></span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken.Equals(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As MappingLockToken) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; bool" Usage="mappingLockToken.Equals other" />
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
        <Parameter Name="other" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="other"></param>
        <summary>
            <span data-ttu-id="8a78b-105">2 つのインスタンスを比較<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />それらが同じ所有者に</span><span class="sxs-lookup"><span data-stu-id="8a78b-105">Compares two instances of <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> to see if they have the same owner</span></span>
            </summary>
        <returns><span data-ttu-id="8a78b-106">両方に属するロック所有者が同じ場合は true。</span><span class="sxs-lookup"><span data-stu-id="8a78b-106">True if they both belong to the same lock owner</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="mappingLockToken.Equals obj" />
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
        <param name="obj"><span data-ttu-id="8a78b-107">現在のオブジェクトと比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8a78b-107">The object to compare with the current object.</span></span></param>
        <summary>
            <span data-ttu-id="8a78b-108">指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="8a78b-108">Determines whether the specified object is equal to the current object.</span></span>
            </summary>
        <returns><span data-ttu-id="8a78b-109">指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="8a78b-109">True if the specified object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceUnlock">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken ForceUnlock;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken ForceUnlock" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken.ForceUnlock" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly ForceUnlock As MappingLockToken " />
      <MemberSignature Language="F#" Value=" staticval mutable ForceUnlock : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken.ForceUnlock" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Security", "CA2104:DoNotDeclareReadOnlyMutableReferenceTypes", Justification="MappingLockToken is an immutable type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a78b-110">トークンを使用できます、ロックされているマッピングに、ロックの解除を設定するには</span><span class="sxs-lookup"><span data-stu-id="8a78b-110">Token that can be used to force an unlock on any locked mapping</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="mappingLockToken.GetHashCode " />
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
            <span data-ttu-id="8a78b-111">このインスタンスのハッシュ コードを計算します。</span><span class="sxs-lookup"><span data-stu-id="8a78b-111">Calculates the hash code for this instance.</span></span>
            </summary>
        <returns><span data-ttu-id="8a78b-112">オブジェクトのハッシュ コード。</span><span class="sxs-lookup"><span data-stu-id="8a78b-112">Hash code for the object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NoLock">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken NoLock;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken NoLock" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken.NoLock" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly NoLock As MappingLockToken " />
      <MemberSignature Language="F#" Value=" staticval mutable NoLock : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken.NoLock" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Security", "CA2104:DoNotDeclareReadOnlyMutableReferenceTypes", Justification="MappingLockToken is an immutable type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a78b-113">マッピングがロックされていない既定の状態を表すトークン</span><span class="sxs-lookup"><span data-stu-id="8a78b-113">Token representing the default state where the mapping isn't locked</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Equality">
      <MemberSignature Language="C#" Value="public static bool operator == (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken leftMappingLockToken, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken rightMappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Equality(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken leftMappingLockToken, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken rightMappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken.op_Equality(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator == (leftMappingLockToken As MappingLockToken, rightMappingLockToken As MappingLockToken) As Boolean" />
      <MemberSignature Language="F#" Value="static member ( = ) : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; bool" Usage="leftMappingLockToken = rightMappingLockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leftMappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
        <Parameter Name="rightMappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="leftMappingLockToken"><span data-ttu-id="8a78b-114"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="8a78b-114">An instance of <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /></span></span></param>
        <param name="rightMappingLockToken"><span data-ttu-id="8a78b-115"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="8a78b-115">An instance of <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /></span></span></param>
        <summary>
            <span data-ttu-id="8a78b-116">等値演算子。</span><span class="sxs-lookup"><span data-stu-id="8a78b-116">Equality operator.</span></span>
            </summary>
        <returns><span data-ttu-id="8a78b-117">ロック所有者が同じに所属させる場合は true。</span><span class="sxs-lookup"><span data-stu-id="8a78b-117">True if both belong to the same lock owner</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Inequality">
      <MemberSignature Language="C#" Value="public static bool operator != (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken leftMappingLockToken, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken rightMappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname bool op_Inequality(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken leftMappingLockToken, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken rightMappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken.op_Inequality(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator != (leftMappingLockToken As MappingLockToken, rightMappingLockToken As MappingLockToken) As Boolean" />
      <MemberSignature Language="F#" Value="static member op_Inequality : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; bool" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken.op_Inequality (leftMappingLockToken, rightMappingLockToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leftMappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
        <Parameter Name="rightMappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="leftMappingLockToken"><span data-ttu-id="8a78b-118"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="8a78b-118">An instance of <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /></span></span></param>
        <param name="rightMappingLockToken"><span data-ttu-id="8a78b-119"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="8a78b-119">An instance of <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /></span></span></param>
        <summary>
            <span data-ttu-id="8a78b-120">非等値演算子。</span><span class="sxs-lookup"><span data-stu-id="8a78b-120">Inequality operator.</span></span>
            </summary>
        <returns><span data-ttu-id="8a78b-121">ロック所有者が同じに所属させる場合は true。</span><span class="sxs-lookup"><span data-stu-id="8a78b-121">True if both belong to the same lock owner</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>