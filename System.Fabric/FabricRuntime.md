<Type Name="FabricRuntime" FullName="System.Fabric.FabricRuntime">
  <TypeSignature Language="C#" Value="public sealed class FabricRuntime : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed FabricRuntime extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricRuntime" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricRuntime&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type FabricRuntime = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>により、ユーザーが作成したホストを取得する、 <see cref="T:System.Fabric.CodePackageActivationContext" />、必要なサービス ファクトリを登録したり、[ <see cref="T:System.Fabric.IStatelessServiceFactory" />、 <see cref="T:System.Fabric.IStatefulServiceFactory" />、または<see cref="T:System.Fabric.ServiceGroupFactory" />] または直接のサービスの種類。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Fabric.FabricRuntime Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.FabricRuntime Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As FabricRuntime" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; System.Fabric.FabricRuntime" Usage="System.Fabric.FabricRuntime.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricRuntime</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>作成、<see cref="T:System.Fabric.FabricRuntime" />オブジェクト。</para>
        </summary>
        <returns>
          <para>新しく作成した<see cref="T:System.Fabric.FabricRuntime" />オブジェクト。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Fabric.FabricRuntime Create (Action fabricExitCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.FabricRuntime Create(class System.Action fabricExitCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.Create(System.Action)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (fabricExitCallback As Action) As FabricRuntime" />
      <MemberSignature Language="F#" Value="static member Create : Action -&gt; System.Fabric.FabricRuntime" Usage="System.Fabric.FabricRuntime.Create fabricExitCallback" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricRuntime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fabricExitCallback" Type="System.Action" />
      </Parameters>
      <Docs>
        <param name="fabricExitCallback">
          <para>ランタイムが終了または終了するときに実行されるアクション。</para>
        </param>
        <summary>
          <para>作成、<see cref="T:System.Fabric.FabricRuntime" />基になるランタイムが終了または何らかの理由が終了した場合に実行される、指定されたコールバック関数を持つオブジェクト。</para>
        </summary>
        <returns>
          <para>新しく作成した<see cref="T:System.Fabric.FabricRuntime" />オブジェクト。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt; CreateAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricRuntime&gt; CreateAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.CreateAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;" Usage="System.Fabric.FabricRuntime.CreateAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する時間の最大量。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。  操作を取り消す必要がある通知を送信するために使用します。  キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>作成、<see cref="T:System.Fabric.FabricRuntime" />に非同期で、指定したオブジェクト<paramref name="timeout" />と<paramref name="cancellationToken" />です。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt; CreateAsync (Action fabricExitCallback, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricRuntime&gt; CreateAsync(class System.Action fabricExitCallback, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.CreateAsync(System.Action,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Action * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;" Usage="System.Fabric.FabricRuntime.CreateAsync (fabricExitCallback, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fabricExitCallback" Type="System.Action" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="fabricExitCallback">
          <para>ランタイムが終了または終了するときに実行されるアクション。</para>
        </param>
        <param name="timeout">
          <para>Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する時間の最大量。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。  操作を取り消す必要がある通知を送信するために使用します。  キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>作成、<see cref="T:System.Fabric.FabricRuntime" />オブジェクト、基になるランタイムが終了または何らかの理由で終了する場合に実行される、指定されたコールバック関数を非同期的に<paramref name="timeout" />、および<paramref name="cancellationToken" />です。 </para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="fabricRuntime.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>破棄、<see cref="T:System.Fabric.FabricRuntime" />です。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetActivationContext">
      <MemberSignature Language="C#" Value="public static System.Fabric.CodePackageActivationContext GetActivationContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.CodePackageActivationContext GetActivationContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetActivationContext" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetActivationContext () As CodePackageActivationContext" />
      <MemberSignature Language="F#" Value="static member GetActivationContext : unit -&gt; System.Fabric.CodePackageActivationContext" Usage="System.Fabric.FabricRuntime.GetActivationContext " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CodePackageActivationContext</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>現在取得<see cref="T:System.Fabric.FabricRuntime" />の<see cref="T:System.Fabric.CodePackageActivationContext" />します。</para>
        </summary>
        <returns>
          <para>アクティベーション コンテキスト。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetActivationContextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.CodePackageActivationContext&gt; GetActivationContextAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.CodePackageActivationContext&gt; GetActivationContextAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetActivationContextAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetActivationContextAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.CodePackageActivationContext&gt;" Usage="System.Fabric.FabricRuntime.GetActivationContextAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.CodePackageActivationContext&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する最長時間</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。  操作を取り消す必要がある通知を送信するために使用します。  キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>現在取得<see cref="T:System.Fabric.FabricRuntime" />の<see cref="T:System.Fabric.CodePackageActivationContext" />に非同期で、指定した<paramref name="timeout" />と<paramref name="cancellationToken" />です。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeContext">
      <MemberSignature Language="C#" Value="public static System.Fabric.NodeContext GetNodeContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.NodeContext GetNodeContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetNodeContext" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetNodeContext () As NodeContext" />
      <MemberSignature Language="F#" Value="static member GetNodeContext : unit -&gt; System.Fabric.NodeContext" Usage="System.Fabric.FabricRuntime.GetNodeContext " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeContext</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Fabric ノードに関する情報を含むノードのコンテキスト オブジェクトを取得します。 </para>
        </summary>
        <returns>
          <para>ノードのコンテキスト。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeContextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.NodeContext&gt; GetNodeContextAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.NodeContext&gt; GetNodeContextAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetNodeContextAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetNodeContextAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NodeContext&gt;" Usage="System.Fabric.FabricRuntime.GetNodeContextAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NodeContext&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する最長時間</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>ノードのコンテキスト Fabric ノードから非同期的にタイムアウトとキャンセル トークン取得します。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceGroupFactory">
      <MemberSignature Language="C#" Value="public void RegisterServiceGroupFactory (string serviceGroupTypeName, System.Fabric.ServiceGroupFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterServiceGroupFactory(string serviceGroupTypeName, class System.Fabric.ServiceGroupFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceGroupFactory(System.String,System.Fabric.ServiceGroupFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterServiceGroupFactory (serviceGroupTypeName As String, factory As ServiceGroupFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceGroupFactory : string * System.Fabric.ServiceGroupFactory -&gt; unit" Usage="fabricRuntime.RegisterServiceGroupFactory (serviceGroupTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.ServiceGroupFactory" />
      </Parameters>
      <Docs>
        <param name="serviceGroupTypeName">
          <para>(文字列) と ServiceGroup サービス型の型名。  これは、マニフェストや CreateServiceGroup コマンドで指定されているサービス グループの種類の型と一致する必要があります。</para>
        </param>
        <param name="factory">
          <para><see cref="T:System.Fabric.ServiceGroupFactory" />指定したサービス グループの種類を作成することができます。</para>
        </param>
        <summary>
          <para>指定した登録<see cref="T:System.Fabric.ServiceGroupFactory" />指定の種類。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceGroupFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterServiceGroupFactoryAsync (string serviceGroupTypeName, System.Fabric.ServiceGroupFactory factory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterServiceGroupFactoryAsync(string serviceGroupTypeName, class System.Fabric.ServiceGroupFactory factory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceGroupFactoryAsync(System.String,System.Fabric.ServiceGroupFactory,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceGroupFactoryAsync : string * System.Fabric.ServiceGroupFactory * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterServiceGroupFactoryAsync (serviceGroupTypeName, factory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.ServiceGroupFactory" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceGroupTypeName">
          <para>(文字列) と ServiceGroup サービス型の型名。  これは、マニフェストや CreateServiceGroup コマンドで指定されているサービス グループの種類の型と一致する必要があります。</para>
        </param>
        <param name="factory">
          <para><see cref="T:System.Fabric.ServiceGroupFactory" />指定したサービス グループの種類を作成することができます。</para>
        </param>
        <param name="timeout">
          <para>Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する時間の最大量。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に、指定した登録<see cref="T:System.Fabric.ServiceGroupFactory" />、指定したサービス グループの種類の指定した<paramref name="timeout" />と<paramref name="cancellationToken" />です。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceType">
      <MemberSignature Language="C#" Value="public void RegisterServiceType (string serviceTypeName, Type serviceTypeImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterServiceType(string serviceTypeName, class System.Type serviceTypeImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceType(System.String,System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterServiceType (serviceTypeName As String, serviceTypeImplementation As Type)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceType : string * Type -&gt; unit" Usage="fabricRuntime.RegisterServiceType (serviceTypeName, serviceTypeImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceTypeImplementation" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>(文字列) としてサービスの種類の型名。  これは、マニフェストや CreateService コマンドで指定されているサービス グループの種類の型と一致する必要があります。</para>
        </param>
        <param name="serviceTypeImplementation">
          <para>指定されたを実装する型の修飾サービス<paramref name="serviceTypeName" />です。</para>
        </param>
        <summary>
          <para>指定したに関連付けます<paramref name="serviceTypeName" />実際にそれを実装する型を管理します。 </para>
        </summary>
        <remarks>
          <para>サービスの種類の登録のためには、このメカニズムは、カスタムを必要とされません<see cref="T:System.Fabric.IStatelessServiceFactory" />または<see cref="T:System.Fabric.IStatefulServiceFactory" />登録時に提供されます。  Service Fabric では、実行時に 1 つを生成し、それを自動的に利用します。  工場出荷時のカスタム実装の必要性がある場合は、実装<see cref="T:System.Fabric.IStatelessServiceFactory" />または<see cref="T:System.Fabric.IStatefulServiceFactory" />うえで、対応するファクトリを使用している登録メソッド (<see cref="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactoryAsync(System.String,System.Fabric.IStatelessServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />または<see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />)</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceTypeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterServiceTypeAsync (string serviceTypeName, Type serviceTypeImplementation, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterServiceTypeAsync(string serviceTypeName, class System.Type serviceTypeImplementation, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceTypeAsync(System.String,System.Type,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceTypeAsync : string * Type * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterServiceTypeAsync (serviceTypeName, serviceTypeImplementation, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceTypeImplementation" Type="System.Type" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>(文字列) としてサービスの種類の型名。  これは、マニフェストや CreateService コマンドで指定されているサービス グループの種類の型と一致する必要があります。</para>
        </param>
        <param name="serviceTypeImplementation">
          <para>指定されたを実装する型の修飾サービス<paramref name="serviceTypeName" />です。</para>
        </param>
        <param name="timeout">
          <para>Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する時間の最大量。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。  操作を取り消す必要がある通知を送信するために使用します。  キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に指定された serviceTypeName を実装して、指定した実際のマネージ型に関連付けます<paramref name="timeout" />と<paramref name="cancellationToken" /></para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatefulServiceFactory">
      <MemberSignature Language="C#" Value="public void RegisterStatefulServiceFactory (string serviceTypeName, System.Fabric.IStatefulServiceFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterStatefulServiceFactory(string serviceTypeName, class System.Fabric.IStatefulServiceFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactory(System.String,System.Fabric.IStatefulServiceFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterStatefulServiceFactory (serviceTypeName As String, factory As IStatefulServiceFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatefulServiceFactory : string * System.Fabric.IStatefulServiceFactory -&gt; unit" Usage="fabricRuntime.RegisterStatefulServiceFactory (serviceTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatefulServiceFactory" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>(文字列) としてサービスの種類の型名。  これは、マニフェストや CreateService コマンドで指定されているサービス グループの種類の型と一致する必要があります。</para>
        </param>
        <param name="factory">
          <para><see cref="T:System.Fabric.IStatefulServiceFactory" />指定されたサービス型を作成することができます。</para>
        </param>
        <summary>
          <para>指定した登録<see cref="T:System.Fabric.IStatefulServiceFactory" />指定されたサービスの種類。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatefulServiceFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterStatefulServiceFactoryAsync (string serviceTypeName, System.Fabric.IStatefulServiceFactory factory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterStatefulServiceFactoryAsync(string serviceTypeName, class System.Fabric.IStatefulServiceFactory factory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatefulServiceFactoryAsync : string * System.Fabric.IStatefulServiceFactory * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterStatefulServiceFactoryAsync (serviceTypeName, factory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatefulServiceFactory" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>(文字列) としてサービスの種類の型名。  これは、マニフェストや CreateService コマンドで指定されているサービス グループの種類の型と一致する必要があります。</para>
        </param>
        <param name="factory">
          <para><see cref="T:System.Fabric.IStatefulServiceFactory" />指定されたサービス型を作成することができます。</para>
        </param>
        <param name="timeout">
          <para>Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する時間の最大量。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。  操作を取り消す必要がある通知を送信するために使用します。  キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>指定した登録<see cref="T:System.Fabric.IStatefulServiceFactory" />、指定されたサービスの種類の指定した<paramref name="timeout" />と<paramref name="cancellationToken" />です。</para>
        </summary>
        <returns>
          <para>操作を表す非同期です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatelessServiceFactory">
      <MemberSignature Language="C#" Value="public void RegisterStatelessServiceFactory (string serviceTypeName, System.Fabric.IStatelessServiceFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterStatelessServiceFactory(string serviceTypeName, class System.Fabric.IStatelessServiceFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactory(System.String,System.Fabric.IStatelessServiceFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterStatelessServiceFactory (serviceTypeName As String, factory As IStatelessServiceFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatelessServiceFactory : string * System.Fabric.IStatelessServiceFactory -&gt; unit" Usage="fabricRuntime.RegisterStatelessServiceFactory (serviceTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatelessServiceFactory" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>(文字列) としてサービスの種類の型名。  これは、マニフェストや CreateService コマンドで指定されているサービス グループの種類の型と一致する必要があります。</para>
        </param>
        <param name="factory">
          <para><see cref="T:System.Fabric.IStatelessServiceFactory" />指定されたサービス型を作成することができます。</para>
        </param>
        <summary>
          <para>指定した登録<see cref="T:System.Fabric.IStatelessServiceFactory" />指定されたサービスの種類。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatelessServiceFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterStatelessServiceFactoryAsync (string serviceTypeName, System.Fabric.IStatelessServiceFactory factory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterStatelessServiceFactoryAsync(string serviceTypeName, class System.Fabric.IStatelessServiceFactory factory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactoryAsync(System.String,System.Fabric.IStatelessServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatelessServiceFactoryAsync : string * System.Fabric.IStatelessServiceFactory * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterStatelessServiceFactoryAsync (serviceTypeName, factory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatelessServiceFactory" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>(文字列) としてサービスの種類の型名。  これは、マニフェストや CreateService コマンドで指定されているサービス グループの種類の型と一致する必要があります。</para>
        </param>
        <param name="factory">
          <para><see cref="T:System.Fabric.IStatelessServiceFactory" />指定されたサービス型を作成することができます。</para>
        </param>
        <param name="timeout">
          <para>Service Fabric は、TimeoutException を返す前に続行するには、この操作を許可する時間の最大量。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。  操作を取り消す必要がある通知を送信するために使用します。  キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に、指定した登録<see cref="T:System.Fabric.IStatelessServiceFactory" />、指定したサービス型を指定した<paramref name="timeout" />と<paramref name="cancellationToken" /></para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>