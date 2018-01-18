<Type Name="RemoteReplicatorAcknowledgementDetail" FullName="System.Fabric.Query.RemoteReplicatorAcknowledgementDetail">
  <TypeSignature Language="C#" Value="public sealed class RemoteReplicatorAcknowledgementDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RemoteReplicatorAcknowledgementDetail extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RemoteReplicatorAcknowledgementDetail" />
  <TypeSignature Language="F#" Value="type RemoteReplicatorAcknowledgementDetail = class" />
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
            <span data-ttu-id="1f9ea-101">レプリケーションまたはコピー ストリームに関連する受信確認の詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="1f9ea-101">Provides acknowledgement details pertaining to a replication or copy stream.</span></span> <span data-ttu-id="1f9ea-102">メンバー<see cref="T:System.Fabric.Query.RemoteReplicatorStatus" /></span><span class="sxs-lookup"><span data-stu-id="1f9ea-102">Member of <see cref="T:System.Fabric.Query.RemoteReplicatorStatus" /></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RemoteReplicatorAcknowledgementDetail ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="1f9ea-103"><see cref="T:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1f9ea-103">Initializes a new instance of the <see cref="T:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageApplyDuration">
      <MemberSignature Language="C#" Value="public TimeSpan AverageApplyDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AverageApplyDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.AverageApplyDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AverageApplyDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AverageApplyDuration : TimeSpan" Usage="System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.AverageApplyDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1f9ea-104">操作を適用するための平均実行時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="1f9ea-104">Gets the average duration for applying operations</span></span>
            </summary>
        <value>
          <para><span data-ttu-id="1f9ea-105">表す平均では、レプリケーターのリモート インスタンスの実行時間が適用されます。</span><span class="sxs-lookup"><span data-stu-id="1f9ea-105">Represents the average apply duration for a remote replicator instance.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageReceiveDuration">
      <MemberSignature Language="C#" Value="public TimeSpan AverageReceiveDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AverageReceiveDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.AverageReceiveDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AverageReceiveDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AverageReceiveDuration : TimeSpan" Usage="System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.AverageReceiveDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1f9ea-106">操作のための ack を受信するための平均実行時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="1f9ea-106">Gets the average duration for receiving acks for operations</span></span>
            </summary>
        <value>
          <para><span data-ttu-id="1f9ea-107">レプリケーターのリモート インスタンスの実行時間を受信平均を表します。</span><span class="sxs-lookup"><span data-stu-id="1f9ea-107">Represents the average receive duration for a remote replicator instance.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotReceivedCount">
      <MemberSignature Language="C#" Value="public long NotReceivedCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NotReceivedCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.NotReceivedCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NotReceivedCount As Long" />
      <MemberSignature Language="F#" Value="member this.NotReceivedCount : int64" Usage="System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.NotReceivedCount" />
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
            <span data-ttu-id="1f9ea-108">まだ受信操作の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="1f9ea-108">Gets the number of operations not yet received</span></span>
            </summary>
        <value>
          <para><span data-ttu-id="1f9ea-109">リモートのレプリケーターによって受信されていない操作の数を表します。</span><span class="sxs-lookup"><span data-stu-id="1f9ea-109">Represents the number of operations not yet received by a remote replicator.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceivedAndNotAppliedCount">
      <MemberSignature Language="C#" Value="public long ReceivedAndNotAppliedCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReceivedAndNotAppliedCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.ReceivedAndNotAppliedCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceivedAndNotAppliedCount As Long" />
      <MemberSignature Language="F#" Value="member this.ReceivedAndNotAppliedCount : int64" Usage="System.Fabric.Query.RemoteReplicatorAcknowledgementDetail.ReceivedAndNotAppliedCount" />
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
            <span data-ttu-id="1f9ea-110">受信され、適用されない操作の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="1f9ea-110">Gets the number of operations received and not applied</span></span>
            </summary>
        <value>
          <para><span data-ttu-id="1f9ea-111">受信され、リモートのレプリケーターによって適用されていない操作の数を表します。</span><span class="sxs-lookup"><span data-stu-id="1f9ea-111">Represents the number of operations received and not yet applied by a remote replicator.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>