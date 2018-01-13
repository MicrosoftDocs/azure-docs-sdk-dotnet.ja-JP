<Type Name="ReplicatorQueueStatus" FullName="System.Fabric.Query.ReplicatorQueueStatus">
  <TypeSignature Language="C#" Value="public sealed class ReplicatorQueueStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicatorQueueStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ReplicatorQueueStatus" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicatorQueueStatus" />
  <TypeSignature Language="F#" Value="type ReplicatorQueueStatus = class" />
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
      <para>Service Fabric レプリケーターに使用するキューのさまざまな統計情報を提供します。</para>
    </summary>
    <remarks>
      <para>レプリケーターの役割によって (<see cref="F:System.Fabric.ReplicaRole.Primary" />または<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />)、この型のプロパティが異なる状況を意味します。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicatorQueueStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ReplicatorQueueStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Query.ReplicatorQueueStatus" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommittedSequenceNumber">
      <MemberSignature Language="C#" Value="public long CommittedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CommittedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.CommittedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CommittedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.CommittedSequenceNumber : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.CommittedSequenceNumber" />
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
          <para>「解説」を参照してください。</para>
        </summary>
        <value>
          <para>コミットされたシーケンス番号。</para>
        </value>
        <remarks>
          <list type="number">
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.Primary" />– を一番大きいシーケンス番号を表す、<b>クォーラム</b>のセカンダリ レプリカが、操作を適用します。</para>
              </description>
            </item>
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />– プライマリからセカンダリにレプリケーターによって受信されたが最大のシーケンス番号を表します。</para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompletedSequenceNumber">
      <MemberSignature Language="C#" Value="public long CompletedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CompletedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.CompletedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CompletedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.CompletedSequenceNumber : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.CompletedSequenceNumber" />
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
          <para>「解説」を参照してください。</para>
        </summary>
        <value>
          <para>完了したシーケンス番号。</para>
        </value>
        <remarks>
          <list type="number">
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.Primary" />– を一番大きいシーケンス番号を表す<b>すべて</b>セカンダリ レプリカが、操作を適用します。</para>
              </description>
            </item>
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />– ユーザーのサービスのレプリカによって適用されている最大のシーケンス番号を表します。</para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="FirstSequenceNumber">
      <MemberSignature Language="C#" Value="public long FirstSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 FirstSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.FirstSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FirstSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.FirstSequenceNumber : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.FirstSequenceNumber" />
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
          <para>「解説」を参照してください。</para>
        </summary>
        <value>
          <para>最初のシーケンス番号。</para>
        </value>
        <remarks>
          <list type="number">
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.Primary" />– キューに存在する操作の最小値のシーケンス番号を表します。 値は同じになります<see cref="P:System.Fabric.Query.ReplicatorQueueStatus.CompletedSequenceNumber" />、すべてのセカンダリ レプリカから受信確認を受信した後、プライマリのレプリケーターが操作を破棄します。</para>
              </description>
            </item>
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />– キューで利用可能な最初の操作のシーケンス番号を表します。</para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.LastSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastSequenceNumber : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.LastSequenceNumber" />
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
          <para>「解説」を参照してください。</para>
        </summary>
        <value>
          <para>最後のシーケンス番号。</para>
        </value>
        <remarks>
          <list type="number">
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.Primary" />– キューで提供される操作の最後のシーケンス番号を表します。</para>
              </description>
            </item>
            <item>
              <description>
                <para>
                  <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />– キューで提供される操作の最後のシーケンス番号を表します。</para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueMemorySize">
      <MemberSignature Language="C#" Value="public long QueueMemorySize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 QueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.QueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueueMemorySize As Long" />
      <MemberSignature Language="F#" Value="member this.QueueMemorySize : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.QueueMemorySize" />
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
          <para>キューが使用されている仮想メモリ バイト数を取得します。</para>
        </summary>
        <value>
          <para>キューが使用されている仮想メモリ バイト数。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueUtilizationPercentage">
      <MemberSignature Language="C#" Value="public long QueueUtilizationPercentage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 QueueUtilizationPercentage" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ReplicatorQueueStatus.QueueUtilizationPercentage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueueUtilizationPercentage As Long" />
      <MemberSignature Language="F#" Value="member this.QueueUtilizationPercentage : int64" Usage="System.Fabric.Query.ReplicatorQueueStatus.QueueUtilizationPercentage" />
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
          <para>キューの使用率を取得します。</para>
        </summary>
        <value>
          <para>キューの使用率。</para>
        </value>
        <remarks>
          <para>値が '0' のことを示し、キューが空 '100' の値は、キューがいっぱいであることを示します。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>