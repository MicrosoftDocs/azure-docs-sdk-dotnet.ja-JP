<Type Name="MoveSecondaryResult" FullName="System.Fabric.Result.MoveSecondaryResult">
  <TypeSignature Language="C#" Value="public class MoveSecondaryResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MoveSecondaryResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.MoveSecondaryResult" />
  <TypeSignature Language="VB.NET" Value="Public Class MoveSecondaryResult" />
  <TypeSignature Language="F#" Value="type MoveSecondaryResult = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0567b-101">セカンダリ レプリカの結果オブジェクトを表しますに移動します。</span><span class="sxs-lookup"><span data-stu-id="0567b-101">Represents move secondary replica result object.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="0567b-102">このクラスは、セカンダリ レプリカが現在移動、newSecondaryNodeName、SelectedReplica の移動先を選択したセカンダリ レプリカを表す SelectedPartition 情報の前に、currentSecondaryNodeName を返します。</span><span class="sxs-lookup"><span data-stu-id="0567b-102">This class returns currentSecondaryNodeName, where secondary replica was present before movement, newSecondaryNodeName where the SelectedReplica is moved and SelectedPartition information that represents the selected secondary replica.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="CurrentSecondaryNodeName">
      <MemberSignature Language="C#" Value="public string CurrentSecondaryNodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentSecondaryNodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.MoveSecondaryResult.CurrentSecondaryNodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentSecondaryNodeName As String" />
      <MemberSignature Language="F#" Value="member this.CurrentSecondaryNodeName : string" Usage="System.Fabric.Result.MoveSecondaryResult.CurrentSecondaryNodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0567b-103">対象のセカンダリ レプリカの現在のノード名を取得します。</span><span class="sxs-lookup"><span data-stu-id="0567b-103">Gets current node name for the target secondary replica.</span></span>
            </summary>
        <value><span data-ttu-id="0567b-104">対象のセカンダリ レプリカのノード名。</span><span class="sxs-lookup"><span data-stu-id="0567b-104">The node name for the target secondary replica.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NewSecondaryNodeName">
      <MemberSignature Language="C#" Value="public string NewSecondaryNodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NewSecondaryNodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.MoveSecondaryResult.NewSecondaryNodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NewSecondaryNodeName As String" />
      <MemberSignature Language="F#" Value="member this.NewSecondaryNodeName : string" Usage="System.Fabric.Result.MoveSecondaryResult.NewSecondaryNodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0567b-105">ここでセカンダリ レプリカの移動先とノード名を取得します。</span><span class="sxs-lookup"><span data-stu-id="0567b-105">Gets node name where secondary replica will move to.</span></span>
            </summary>
        <value><span data-ttu-id="0567b-106">ここで、ターゲット セカンダリ レプリカの移動先と、ノードの名前。</span><span class="sxs-lookup"><span data-stu-id="0567b-106">The name of the node where the target secondary replica will move to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectedPartition">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedPartition SelectedPartition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedPartition SelectedPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.MoveSecondaryResult.SelectedPartition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedPartition As SelectedPartition" />
      <MemberSignature Language="F#" Value="member this.SelectedPartition : System.Fabric.SelectedPartition" Usage="System.Fabric.Result.MoveSecondaryResult.SelectedPartition" />
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
            <span data-ttu-id="0567b-107">選択したパーティションを取得します。</span><span class="sxs-lookup"><span data-stu-id="0567b-107">Gets the selected partition.</span></span>
            </summary>
        <value><span data-ttu-id="0567b-108">SelectedPartition オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="0567b-108">The SelectedPartition object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.MoveSecondaryResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="moveSecondaryResult.ToString " />
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
            <span data-ttu-id="0567b-109">書式 CurrentSecondaryNodeName、NewSecondaryNodeName、および SelectedPartition 文字列に変換します。</span><span class="sxs-lookup"><span data-stu-id="0567b-109">Formats CurrentSecondaryNodeName, NewSecondaryNodeName, and SelectedPartition into a string.</span></span>
            </summary>
        <returns><span data-ttu-id="0567b-110">書式設定された文字列。</span><span class="sxs-lookup"><span data-stu-id="0567b-110">The formatted string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>