<Type Name="SelectedReplica" FullName="System.Fabric.SelectedReplica">
  <TypeSignature Language="C#" Value="public class SelectedReplica : IEquatable&lt;System.Fabric.SelectedReplica&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SelectedReplica extends System.Object implements class System.IEquatable`1&lt;class System.Fabric.SelectedReplica&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.SelectedReplica" />
  <TypeSignature Language="VB.NET" Value="Public Class SelectedReplica&#xA;Implements IEquatable(Of SelectedReplica)" />
  <TypeSignature Language="F#" Value="type SelectedReplica = class&#xA;    interface IEquatable&lt;SelectedReplica&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;System.Fabric.SelectedReplica&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="22f73-101">返しますでは、ReplicaSelector テストの容易性 API を使用してレプリカ オブジェクトを選択します。</span><span class="sxs-lookup"><span data-stu-id="22f73-101">Returns selected replica object using ReplicaSelector testability API.</span></span>
            </summary>
    <remarks> 
            <span data-ttu-id="22f73-102">このクラスは、選択したレプリカ セレクター テストの容易性 API を使用して、選択したレプリカに関する情報を返します。</span><span class="sxs-lookup"><span data-stu-id="22f73-102">This class returns information about the selected replica selected using replica selector testability API.</span></span> <span data-ttu-id="22f73-103">このクラスを選択したレプリカの ReplicaOrInstance ID と PartitionSelector が表示されます RandomOf オーバー ロードを使用して、ReplicaSelector が生成された場合</span><span class="sxs-lookup"><span data-stu-id="22f73-103">If the ReplicaSelector was generated using the RandomOf overload this class will be populated with ReplicaOrInstance ID and PartitionSelector for the selected replica</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (System.Fabric.SelectedReplica other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class System.Fabric.SelectedReplica other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.SelectedReplica.Equals(System.Fabric.SelectedReplica)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As SelectedReplica) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : System.Fabric.SelectedReplica -&gt; bool" Usage="selectedReplica.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.SelectedReplica" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="22f73-104">現在 SelectedReplica が比較するのには、選択したレプリカです。</span><span class="sxs-lookup"><span data-stu-id="22f73-104">A selected replica with which the current SelectedReplica is to be compared.</span></span></param>
        <summary>
            <span data-ttu-id="22f73-105">この SelectedReplica 他 SelectedReplica とを比較します。</span><span class="sxs-lookup"><span data-stu-id="22f73-105">Compares this SelectedReplica with other SelectedReplica.</span></span>
            </summary>
        <returns><span data-ttu-id="22f73-106">ReplicaOrInstanceId と SelectedPartition、2 つの SelectedReplica オブジェクトの両方が一致する場合は true。それ以外の場合は false を返します。</span><span class="sxs-lookup"><span data-stu-id="22f73-106">True, if both replicaOrInstanceId and SelectedPartition, of the two SelectedReplica objects match; else returns false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="public static readonly System.Fabric.SelectedReplica None;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class System.Fabric.SelectedReplica None" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SelectedReplica.None" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly None As SelectedReplica " />
      <MemberSignature Language="F#" Value=" staticval mutable None : System.Fabric.SelectedReplica" Usage="System.Fabric.SelectedReplica.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SelectedReplica</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f73-107">None が返されますレプリカ セレクター。</span><span class="sxs-lookup"><span data-stu-id="22f73-107">Returns None replica selector.</span></span> 
            </summary>
        <remarks>
            <span data-ttu-id="22f73-108">SelectedReplica は、テストの容易性 API オーバー ロードを使用する入力としてのレプリカのインスタンス id とパーティション セレクターを受け取らない場合は none になります。</span><span class="sxs-lookup"><span data-stu-id="22f73-108">A SelectedReplica will be none for any testability API with overloads which does not take a replica instance id and partition selector as an input.</span></span> <span data-ttu-id="22f73-109">たとえば RestartNodeAsync が呼び出された場合 ReplicaSelector の代わりにノード名のオーバー ロードとします。</span><span class="sxs-lookup"><span data-stu-id="22f73-109">For example if RestartNodeAsync is called with the NodeName overload instead of ReplicaSelector.</span></span> <span data-ttu-id="22f73-110">返される ReplicaSelector は None という点です。</span><span class="sxs-lookup"><span data-stu-id="22f73-110">Returned ReplicaSelector will be None in that case.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaOrInstanceId">
      <MemberSignature Language="C#" Value="public long ReplicaOrInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaOrInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.SelectedReplica.ReplicaOrInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaOrInstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaOrInstanceId : int64" Usage="System.Fabric.SelectedReplica.ReplicaOrInstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f73-111">レプリカまたはインスタンスの ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="22f73-111">Gets replica or instance ID</span></span>
            </summary>
        <value>
          <para><span data-ttu-id="22f73-112">この SelectedReplica のレプリカまたはインスタンスの ID を返します</span><span class="sxs-lookup"><span data-stu-id="22f73-112">Returns the replica or instance ID for this SelectedReplica</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectedPartition">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedPartition SelectedPartition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedPartition SelectedPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.SelectedReplica.SelectedPartition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedPartition As SelectedPartition" />
      <MemberSignature Language="F#" Value="member this.SelectedPartition : System.Fabric.SelectedPartition" Usage="System.Fabric.SelectedReplica.SelectedPartition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SelectedPartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f73-113">選択したパーティションの取得</span><span class="sxs-lookup"><span data-stu-id="22f73-113">Gets selected partition</span></span> 
            </summary>
        <value>
          <para><span data-ttu-id="22f73-114"><see cref="T:System.Fabric.SelectedReplica" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="22f73-114">Returns <see cref="T:System.Fabric.SelectedReplica" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.SelectedReplica.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="selectedReplica.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="22f73-115">SelectedReplica オブジェクトの文字列表現を返します</span><span class="sxs-lookup"><span data-stu-id="22f73-115">Returns a string representation of SelectedReplica object</span></span>
            </summary>
        <returns><span data-ttu-id="22f73-116">文字列形式を: ReplicaOrInstanceId = &lt;replicaOrInstanceId&gt;、SelectedPartition = &lt;selectedPartition&gt;</span><span class="sxs-lookup"><span data-stu-id="22f73-116">A string with the format: ReplicaOrInstanceId = &lt;replicaOrInstanceId&gt;, SelectedPartition = &lt;selectedPartition&gt;</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>