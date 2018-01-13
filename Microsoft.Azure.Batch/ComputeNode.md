<Type Name="ComputeNode" FullName="Microsoft.Azure.Batch.ComputeNode">
  <TypeSignature Language="C#" Value="public class ComputeNode : Microsoft.Azure.Batch.IInheritedBehaviors, Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNode extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors, class Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ComputeNode" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNode&#xA;Implements IInheritedBehaviors, IRefreshable" />
  <TypeSignature Language="F#" Value="type ComputeNode = class&#xA;    interface IRefreshable&#xA;    interface IInheritedBehaviors&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IRefreshable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            コンピューティング ノードの状態をまとめたものです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AffinityId">
      <MemberSignature Language="C#" Value="public string AffinityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AffinityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.AffinityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AffinityId As String" />
      <MemberSignature Language="F#" Value="member this.AffinityId : string" Usage="Microsoft.Azure.Batch.ComputeNode.AffinityId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンピューティング ノードの場所に関する情報が含まれる非透過の文字列を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AllocationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AllocationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.AllocationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AllocationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.AllocationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この計算ノードがプールに割り当てられ、時間を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.CertificateReference&gt; CertificateReferences { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CertificateReferences As IReadOnlyList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.CertificateReference&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.CertificateReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この計算ノードにインストールされている証明書の一覧を取得します。 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateComputeNodeUser">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNodeUser CreateComputeNodeUser ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.ComputeNodeUser CreateComputeNodeUser() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.CreateComputeNodeUser" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateComputeNodeUser () As ComputeNodeUser" />
      <MemberSignature Language="F#" Value="member this.CreateComputeNodeUser : unit -&gt; Microsoft.Azure.Batch.ComputeNodeUser" Usage="computeNode.CreateComputeNodeUser " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNodeUser</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            呼び出し元によって設定され、Azure Batch のサービスでコンピューティング ノード上でユーザー アカウントを作成するために使用するバインドされていない ComputeNodeUser オブジェクトをインスタンス化します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.ComputeNode" />です。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>これらの動作は、子オブジェクトによって継承されます。</para>
          <para>変更は、コレクションの順序で適用されます。 最後には、wins を記述します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteComputeNodeUser">
      <MemberSignature Language="C#" Value="public void DeleteComputeNodeUser (string userName, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteComputeNodeUser(string userName, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.DeleteComputeNodeUser(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteComputeNodeUser (userName As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteComputeNodeUser : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.DeleteComputeNodeUser (userName, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="userName">削除する ComputeNodeUser の名前。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <summary>
            指定した ComputeNodeUser を削除する呼び出しをブロックしています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteComputeNodeUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteComputeNodeUserAsync (string userName, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteComputeNodeUserAsync(string userName, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.DeleteComputeNodeUserAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteComputeNodeUserAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.DeleteComputeNodeUserAsync (userName, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="userName">削除する ComputeNodeUser の名前。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定した ComputeNodeUser を削除する非同期呼び出しを開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableScheduling">
      <MemberSignature Language="C#" Value="public void DisableScheduling (Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableScheduling(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.DisableScheduling(System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DisableScheduling (disableComputeNodeSchedulingOption As Nullable(Of DisableComputeNodeSchedulingOption), Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DisableScheduling : Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.DisableScheduling (disableComputeNodeSchedulingOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disableComputeNodeSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="disableComputeNodeSchedulingOption">実行中のタスクを行うには新機能を指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />です。</param>
        <summary>
            コンピューティング ノードでタスクのスケジュール設定を無効にします。
            </summary>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.ComputeNode.DisableSchedulingAsync(System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableSchedulingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableSchedulingAsync (Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableSchedulingAsync(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.DisableSchedulingAsync(System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableSchedulingAsync : Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.DisableSchedulingAsync (disableComputeNodeSchedulingOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disableComputeNodeSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="disableComputeNodeSchedulingOption">実行中のタスクを行うには新機能を指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            コンピューティング ノードでタスクのスケジュール設定を無効にします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>この操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableScheduling">
      <MemberSignature Language="C#" Value="public void EnableScheduling (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableScheduling(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.EnableScheduling(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableScheduling (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableScheduling : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.EnableScheduling additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />です。</param>
        <summary>
            コンピューティング ノードでタスクのスケジュール設定を使用できます。
            </summary>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.ComputeNode.EnableScheduling(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSchedulingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableSchedulingAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableSchedulingAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.EnableSchedulingAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableSchedulingAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.EnableSchedulingAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            コンピューティング ノードでタスクのスケジュール設定を使用できます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>この操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNodeEndpointConfiguration EndpointConfiguration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ComputeNodeEndpointConfiguration EndpointConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.EndpointConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndpointConfiguration As ComputeNodeEndpointConfiguration" />
      <MemberSignature Language="F#" Value="member this.EndpointConfiguration : Microsoft.Azure.Batch.ComputeNodeEndpointConfiguration" Usage="Microsoft.Azure.Batch.ComputeNode.EndpointConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNodeEndpointConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンピューティング ノードのエンドポイント構成を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ComputeNodeError&gt; Errors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.ComputeNodeError&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.Errors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Errors As IReadOnlyList(Of ComputeNodeError)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ComputeNodeError&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ComputeNodeError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンピューティング ノードで現在発生しているエラーの一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.NodeFile GetNodeFile (string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.NodeFile GetNodeFile(string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetNodeFile(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeFile (filePath As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As NodeFile" />
      <MemberSignature Language="F#" Value="member this.GetNodeFile : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.NodeFile" Usage="computeNode.GetNodeFile (filePath, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.NodeFile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="filePath">取得するファイルのパス。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <summary>
            指定した NodeFile を取得する呼び出しをブロックしています。
            </summary>
        <returns>バインドされた<see cref="T:Microsoft.Azure.Batch.NodeFile" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync (string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync(string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetNodeFileAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeFileAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="computeNode.GetNodeFileAsync (filePath, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filePath">取得するファイルのパス。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定した NodeFile を取得する非同期の要求を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFile">
      <MemberSignature Language="C#" Value="public void GetRDPFile (System.IO.Stream rdpStream, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetRDPFile(class System.IO.Stream rdpStream, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetRDPFile(System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetRDPFile (rdpStream As Stream, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFile : System.IO.Stream * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.GetRDPFile (rdpStream, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rdpStream" Type="System.IO.Stream" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="rdpStream">RDP ファイル データの書き込み先のストリーム。  このストリームは閉じられたまたはされませんこの呼び出しによって巻き戻されます。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <summary>
            現在のインスタンスのコンピューティング ノードをターゲットとする RDP ファイルのデータを取得し、それを指定したストリームに書き込むへの呼び出しをブロックしています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFile">
      <MemberSignature Language="C#" Value="public void GetRDPFile (string rdpFileNameToCreate, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetRDPFile(string rdpFileNameToCreate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetRDPFile(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetRDPFile (rdpFileNameToCreate As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFile : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.GetRDPFile (rdpFileNameToCreate, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rdpFileNameToCreate" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="rdpFileNameToCreate">作成する RDP ファイルの名前。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <summary>
            現在のインスタンスのコンピューティング ノードをターゲットとする RDP ファイルのデータを取得し、指定した名前のファイルに書き込んだりする呼び出しをブロックしています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task GetRDPFileAsync (System.IO.Stream rdpStream, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task GetRDPFileAsync(class System.IO.Stream rdpStream, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetRDPFileAsync(System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFileAsync : System.IO.Stream * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.GetRDPFileAsync (rdpStream, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rdpStream" Type="System.IO.Stream" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="rdpStream">RDP ファイル データの書き込み先のストリーム。  このストリームは閉じられたまたはされませんこの呼び出しによって巻き戻されます。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            現在のインスタンスのコンピューティング ノードをターゲットとする RDP ファイルのデータを取得し、それを指定したストリームに書き込むへの非同期呼び出しを開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task GetRDPFileAsync (string rdpFileNameToCreate, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task GetRDPFileAsync(string rdpFileNameToCreate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetRDPFileAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFileAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.GetRDPFileAsync (rdpFileNameToCreate, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rdpFileNameToCreate" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="rdpFileNameToCreate">作成する RDP ファイルの名前。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            現在のインスタンスのコンピューティング ノードをターゲットとする RDP ファイルのデータを取得し、指定した名前のファイルに書き込んだりする非同期呼び出しを開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteLoginSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.RemoteLoginSettings GetRemoteLoginSettings (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.RemoteLoginSettings GetRemoteLoginSettings(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetRemoteLoginSettings(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRemoteLoginSettings (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As RemoteLoginSettings" />
      <MemberSignature Language="F#" Value="member this.GetRemoteLoginSettings : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.RemoteLoginSettings" Usage="computeNode.GetRemoteLoginSettings additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.RemoteLoginSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />です。</param>
        <summary>
            コンピューティング ノードへのリモート ログイン用に必要な設定を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.ComputeNode.GetRemoteLoginSettingsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
          <para>プールが作成された場合にのみ、このメソッドを呼び出すことができます、<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プロパティです。 このメソッドで作成されたプールで呼び出される場合<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />、Batch サービスが 409 (Conflict) を返します。 指定されているのため、 <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> GetRDPFileAsync/GetRDPFile のいずれかのプロパティを使用する必要があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteLoginSettingsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt; GetRemoteLoginSettingsAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.RemoteLoginSettings&gt; GetRemoteLoginSettingsAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetRemoteLoginSettingsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRemoteLoginSettingsAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt;" Usage="computeNode.GetRemoteLoginSettingsAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            コンピューティング ノードへのリモート ログイン用に必要な設定を取得します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>リモート ログインの設定の取得操作は非同期的に実行されます。</para>
          <para>プールが作成された場合にのみ、このメソッドを呼び出すことができます、<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プロパティです。 このメソッドで作成されたプールで呼び出される場合<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />、Batch サービスが 409 (Conflict) を返します。 指定されているのため、 <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> GetRDPFileAsync/GetRDPFile のいずれかのプロパティを使用する必要があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Batch.ComputeNode.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンピューティング ノードの id を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IPAddress">
      <MemberSignature Language="C#" Value="public string IPAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.IPAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IPAddress As String" />
      <MemberSignature Language="F#" Value="member this.IPAddress : string" Usage="Microsoft.Azure.Batch.ComputeNode.IPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンピューティング ノードに関連付けられている IP アドレスを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDedicated">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDedicated { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDedicated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.IsDedicated" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDedicated As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDedicated : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.IsDedicated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この計算ノードが専用のノードであるかどうかを取得します。 False の場合、優先度の低いノードです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBootTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastBootTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastBootTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.LastBootTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastBootTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastBootTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.LastBootTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンピューティング ノードを開始した時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeFiles">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles (Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles(valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.ListNodeFiles(System.Nullable{System.Boolean},Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListNodeFiles : Nullable&lt;bool&gt; * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="computeNode.ListNodeFiles (recursive, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="recursive">True の場合は、ノードのすべてのファイルの再帰的な一覧を実行します。 False の場合は、ノードのディレクトリのルートにあるファイルのみを返します。</param>
        <param name="detailLevel">Azure Batch Service への呼び出しによって返されるデータの詳細レベルを制御します。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後と、DetailLevel を実装する動作後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <summary>
            ノードのファイルの同期および非同期の列挙型を公開します。
            </summary>
        <returns>同期または非同期のどちらかのパターンを使用してオブジェクトの列挙に使用できる IPagedEnumerable のインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reboot">
      <MemberSignature Language="C#" Value="public void Reboot (Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Reboot(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.Reboot(System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reboot (Optional rebootOption As Nullable(Of ComputeNodeRebootOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Reboot : Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.Reboot (rebootOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="rebootOption">再起動に関連付けられている再起動オプション。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <summary>
            コンピューティング ノードを再起動する呼び出しをブロックしています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RebootAsync (Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RebootAsync(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.RebootAsync(System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RebootAsync : Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.RebootAsync (rebootOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="rebootOption">再起動に関連付けられている再起動オプション。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            コンピューティング ノードを再起動する非同期呼び出しを開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecentTasks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.TaskInformation&gt; RecentTasks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.TaskInformation&gt; RecentTasks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.RecentTasks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecentTasks As IReadOnlyList(Of TaskInformation)" />
      <MemberSignature Language="F#" Value="member this.RecentTasks : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.TaskInformation&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.RecentTasks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.TaskInformation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この計算ノード上で実行された最新のタスクの実行情報を取得します。 この要素が、現在のプールに割り当てられた時刻以降には、少なくとも 1 つのタスクがこのコンピューティング ノード上で実行された場合のみ返されることに注意してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public void Refresh (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Refresh(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit&#xA;override this.Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.Refresh (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel">最新の更新の詳細レベルです。 詳細レベルを省略する場合、<see cref="P:Microsoft.Azure.Batch.ComputeNode.Id" />プロパティを指定すると、更新は失敗します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />です。</param>
        <summary>
            更新、<see cref="T:Microsoft.Azure.Batch.ComputeNode" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.RefreshAsync (detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.ComputeNode/&lt;RefreshAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="detailLevel">最新の更新の詳細レベルです。 詳細レベルを省略する場合、<see cref="P:Microsoft.Azure.Batch.ComputeNode.Id" />プロパティを指定すると、更新は失敗します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            現在の更新<see cref="T:Microsoft.Azure.Batch.ComputeNode" />です。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />非同期更新操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reimage">
      <MemberSignature Language="C#" Value="public void Reimage (Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Reimage(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.Reimage(System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reimage (Optional reimageOption As Nullable(Of ComputeNodeReimageOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Reimage : Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.Reimage (reimageOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="reimageOption">再イメージ化に関連付けられているイメージを再作成のオプションです。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <summary>
            コンピューティング ノードの再イメージ化への呼び出しをブロックしています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReimageAsync (Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ReimageAsync(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.ReimageAsync(System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ReimageAsync : Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.ReimageAsync (reimageOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="reimageOption">再イメージ化に関連付けられているイメージを再作成のオプションです。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            コンピューティング ノードの再イメージ化への非同期呼び出しを開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.RemoveFromPool(System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.RemoveFromPool (deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="deallocationOption">
            処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。
            </param>
        <param name="resizeTimeout">RemoveFromPool 操作が Azure Batch のシステムで終了するまでにかかる時間の最大量。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <summary>
            プールから、コンピューティング ノードを削除する要求をブロックしています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.RemoveFromPoolAsync(System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.RemoveFromPoolAsync (deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deallocationOption">
            処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。 既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。
            </param>
        <param name="resizeTimeout">RemoveFromPool 操作が Azure Batch のシステムで終了するまでにかかる時間の最大量。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            プールから、コンピューティング ノードを削除する非同期呼び出しを開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunningTasksCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RunningTasksCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RunningTasksCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.RunningTasksCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RunningTasksCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RunningTasksCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.RunningTasksCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンピューティング ノードでは、実行中のタスクの合計数を取得します。 ジョブの準備、ジョブのリリースでは、これが含まれていて、ジョブ マネージャー タスクがプールではないタスクを開始します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulingState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.SchedulingState&gt; SchedulingState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.SchedulingState&gt; SchedulingState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.SchedulingState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SchedulingState As Nullable(Of SchedulingState)" />
      <MemberSignature Language="F#" Value="member this.SchedulingState : Nullable&lt;Microsoft.Azure.Batch.Common.SchedulingState&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.SchedulingState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.SchedulingState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ノードがタスクのスケジュール設定に使用できるかどうかを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.StartTask StartTask { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.StartTask" Usage="Microsoft.Azure.Batch.ComputeNode.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このプール内のすべてのコンピューティング ノードに関連付けられている開始タスクを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTaskInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.StartTaskInformation StartTaskInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.StartTaskInformation StartTaskInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.StartTaskInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTaskInformation As StartTaskInformation" />
      <MemberSignature Language="F#" Value="member this.StartTaskInformation : Microsoft.Azure.Batch.StartTaskInformation" Usage="Microsoft.Azure.Batch.ComputeNode.StartTaskInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.StartTaskInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在の状態、エラーの詳細、終了コード、開始時刻、終了時刻などを含む、開始タスクの詳細なランタイム情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of ComputeNodeState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeState&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンピューティング ノードの現在の状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在の状態、コンピューティング ノードになった時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalTasksRun">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalTasksRun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalTasksRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.TotalTasksRun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalTasksRun As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalTasksRun : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.TotalTasksRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このプールに割り当てられた時刻からこのコンピューティング ノード上で実行が完了したタスクの数を取得します。 ジョブの準備、ジョブのリリースでは、これが含まれていて、ジョブ マネージャー タスクがプールではないタスクを開始します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalTasksSucceeded">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalTasksSucceeded { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalTasksSucceeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.TotalTasksSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalTasksSucceeded As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalTasksSucceeded : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.TotalTasksSucceeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            完了したタスクの合計数を取得しました (exitCode 0) の計算ノードにします。 ジョブの準備、ジョブのリリースでは、これが含まれていて、ジョブ マネージャー タスクがプールではないタスクを開始します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.ComputeNode.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンピューティング ノードの URL を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineSize">
      <MemberSignature Language="C#" Value="public string VirtualMachineSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.VirtualMachineSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineSize As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineSize : string" Usage="Microsoft.Azure.Batch.ComputeNode.VirtualMachineSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンピューティング ノードをホストする仮想マシンのサイズを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>