<Type Name="IReplicator" FullName="System.Fabric.IReplicator">
  <TypeSignature Language="C#" Value="public interface IReplicator : System.Fabric.IPrimaryReplicator" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReplicator implements class System.Fabric.IPrimaryReplicator" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IReplicator" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReplicator&#xA;Implements IPrimaryReplicator" />
  <TypeSignature Language="F#" Value="type IReplicator = interface&#xA;    interface IPrimaryReplicator" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IPrimaryReplicator</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iReplicator.Abort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</summary>
        <remarks />
      </Docs>
    </Member>
    <Member MemberName="ChangeRoleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ChangeRoleAsync (System.Fabric.Epoch epoch, System.Fabric.ReplicaRole role, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ChangeRoleAsync(valuetype System.Fabric.Epoch epoch, valuetype System.Fabric.ReplicaRole role, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.ChangeRoleAsync(System.Fabric.Epoch,System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeRoleAsync : System.Fabric.Epoch * System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReplicator.ChangeRoleAsync (epoch, role, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="role" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</para>
        </param>
        <param name="role">
          <para>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReplicator.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCatchUpCapability">
      <MemberSignature Language="C#" Value="public long GetCatchUpCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 GetCatchUpCapability() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.GetCatchUpCapability" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCatchUpCapability () As Long" />
      <MemberSignature Language="F#" Value="abstract member GetCatchUpCapability : unit -&gt; int64" Usage="iReplicator.GetCatchUpCapability " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</summary>
        <returns>
          <para>内部使用のみ。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCurrentProgress">
      <MemberSignature Language="C#" Value="public long GetCurrentProgress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 GetCurrentProgress() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.GetCurrentProgress" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCurrentProgress () As Long" />
      <MemberSignature Language="F#" Value="abstract member GetCurrentProgress : unit -&gt; int64" Usage="iReplicator.GetCurrentProgress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</summary>
        <returns>
          <para>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.OpenAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iReplicator.OpenAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateEpochAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateEpochAsync (System.Fabric.Epoch epoch, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateEpochAsync(valuetype System.Fabric.Epoch epoch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IReplicator.UpdateEpochAsync(System.Fabric.Epoch,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateEpochAsync : System.Fabric.Epoch * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReplicator.UpdateEpochAsync (epoch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</summary>
        <returns>
          <para>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>