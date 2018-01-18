<Type Name="SelectedPartition" FullName="System.Fabric.SelectedPartition">
  <TypeSignature Language="C#" Value="public class SelectedPartition : IEquatable&lt;System.Fabric.SelectedPartition&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SelectedPartition extends System.Object implements class System.IEquatable`1&lt;class System.Fabric.SelectedPartition&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.SelectedPartition" />
  <TypeSignature Language="VB.NET" Value="Public Class SelectedPartition&#xA;Implements IEquatable(Of SelectedPartition)" />
  <TypeSignature Language="F#" Value="type SelectedPartition = class&#xA;    interface IEquatable&lt;SelectedPartition&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;System.Fabric.SelectedPartition&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="5d0a7-101">PartitionSelector FaultManagementClient Api を使用して選択したパーティションを返します。</span><span class="sxs-lookup"><span data-stu-id="5d0a7-101">Returns selected partition using PartitionSelector FaultManagementClient APIs.</span></span> 
            </summary>
    <remarks> 
            <span data-ttu-id="5d0a7-102">このクラスは、PartitionSelector テストの容易性 API を使用して選択されたパーティションに関する情報を返します。</span><span class="sxs-lookup"><span data-stu-id="5d0a7-102">This class returns information about the partition that was selected using PartitionSelector testability API.</span></span>
            <span data-ttu-id="5d0a7-103">たとえば、PartitionSelector は、このクラスは、サービス名およびパーティションの id を表示する RandomOf オーバー ロードを使用して作成された場合、選択したパーティションの</span><span class="sxs-lookup"><span data-stu-id="5d0a7-103">For example if the PartitionSelector was created using the RandomOf overload this class will populate service name and partition id of the for selected partition</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (System.Fabric.SelectedPartition other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class System.Fabric.SelectedPartition other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.SelectedPartition.Equals(System.Fabric.SelectedPartition)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As SelectedPartition) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : System.Fabric.SelectedPartition -&gt; bool" Usage="selectedPartition.Equals other" />
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
        <Parameter Name="other" Type="System.Fabric.SelectedPartition" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="5d0a7-104">現在 SelectedPartition が比較するのには、選択したパーティション。</span><span class="sxs-lookup"><span data-stu-id="5d0a7-104">A selected partition with which the current SelectedPartition is to be compared.</span></span></param>
        <summary>
            <span data-ttu-id="5d0a7-105">この SelectedPartition 他 SelectedPartition とを比較します。</span><span class="sxs-lookup"><span data-stu-id="5d0a7-105">Compares this SelectedPartition with other SelectedPartition.</span></span>
            </summary>
        <returns><span data-ttu-id="5d0a7-106">両方のサービス名とパーティションの ID が 2 つの場合は true。 SelectedPartition オブジェクトと一致します。それ以外の場合は false を返します。</span><span class="sxs-lookup"><span data-stu-id="5d0a7-106">True, if both service name and partition ID of the two SelectedPartition objects match; else returns false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="public static readonly System.Fabric.SelectedPartition None;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class System.Fabric.SelectedPartition None" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SelectedPartition.None" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly None As SelectedPartition " />
      <MemberSignature Language="F#" Value=" staticval mutable None : System.Fabric.SelectedPartition" Usage="System.Fabric.SelectedPartition.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SelectedPartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d0a7-107">セレクターをパーティション分割なしを返します。</span><span class="sxs-lookup"><span data-stu-id="5d0a7-107">Returns none partition selector.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="5d0a7-108">SelectedPartition は、テストの容易性 API オーバー ロードを使用する入力として、パーティションまたはレプリカ セレクターを受け取らない場合は none になります。</span><span class="sxs-lookup"><span data-stu-id="5d0a7-108">A SelectedPartition will be none for any testability API with overloads which does not take a partition or replica selector as an input.</span></span> <span data-ttu-id="5d0a7-109">PartitionSelector が返されます ReplicaSelector ではなく、ノード名のオーバー ロードで RestartNodeAsync が呼び出された場合の例には、None を指定されます。</span><span class="sxs-lookup"><span data-stu-id="5d0a7-109">For example if RestartNodeAsync is called with the NodeName overload instead of ReplicaSelector then PartitionSelector returned will be None</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.SelectedPartition.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.SelectedPartition.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d0a7-110">パーティション ID を GUID として取得します。</span><span class="sxs-lookup"><span data-stu-id="5d0a7-110">Gets the partition ID as GUID</span></span>
            </summary>
        <value>
            <span data-ttu-id="5d0a7-111">GUID</span><span class="sxs-lookup"><span data-stu-id="5d0a7-111">A GUID</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.SelectedPartition.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.SelectedPartition.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d0a7-112">URI として、サービス名を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d0a7-112">Gets the service name as URI</span></span>
            </summary>
        <value>
            <span data-ttu-id="5d0a7-113">URI</span><span class="sxs-lookup"><span data-stu-id="5d0a7-113">A URI</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.SelectedPartition.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="selectedPartition.ToString " />
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
            <span data-ttu-id="5d0a7-114">SelectedPartition オブジェクトの文字列表現を取得します</span><span class="sxs-lookup"><span data-stu-id="5d0a7-114">Gets a string representation of the SelectedPartition object</span></span>
            </summary>
        <returns><span data-ttu-id="5d0a7-115">文字列形式を: サービス名:&lt;サービス名&gt;、パーティション Id:&lt;パーティション id&gt;</span><span class="sxs-lookup"><span data-stu-id="5d0a7-115">A string with the format: Service Name: &lt;service-name&gt;, Partition Id: &lt;partition-id&gt;</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>