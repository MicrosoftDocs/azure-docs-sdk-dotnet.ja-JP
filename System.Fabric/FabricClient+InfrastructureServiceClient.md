<Type Name="FabricClient+InfrastructureServiceClient" FullName="System.Fabric.FabricClient+InfrastructureServiceClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.InfrastructureServiceClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/InfrastructureServiceClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.InfrastructureServiceClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.InfrastructureServiceClient" />
  <TypeSignature Language="F#" Value="type FabricClient.InfrastructureServiceClient = class" />
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
      <para>インフラストラクチャに固有の操作を実行するためのメソッドを提供します。</para>
      <para>このクラスは、Service Fabric プラットフォームをサポートしていますコードから直接呼び出されるものではありません。</para>
    </summary>
    <remarks>
      <para>このクライアントを使用する前に、InfrastructureService を有効にする必要があります。 InfrastructureService は、いくつかのインフラストラクチャでのみサポートされます。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="InvokeInfrastructureCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureCommandAsync (Uri serviceName, string command);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureCommandAsync(class System.Uri serviceName, string command) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureCommandAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeInfrastructureCommandAsync (serviceName As Uri, command As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureCommandAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureCommandAsync (serviceName, command)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>対象のインフラストラクチャのサービス インスタンスの名前。</para>
        </param>
        <param name="command">
          <para>呼び出されるコマンドのテキスト。  コマンドのコンテンツは、インフラストラクチャに固有です。</para>
        </param>
        <summary>
          <para>指定されたインフラストラクチャのサービス インスタンスで管理コマンドを非同期的に呼び出します。</para>
        </summary>
        <returns>
          <para>インフラストラクチャ サービスからの応答。 応答の形式は、JSON 文字列です。 応答の内容は、どのコマンドが発行されましたによって異なります。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeInfrastructureCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureCommandAsync (Uri serviceName, string command, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureCommandAsync(class System.Uri serviceName, string command, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureCommandAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureCommandAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureCommandAsync (serviceName, command, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>対象のインフラストラクチャのサービス インスタンスの名前。</para>
        </param>
        <param name="command">
          <para>呼び出されるコマンドのテキスト。  コマンドのコンテンツは、インフラストラクチャに固有です。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>インフラストラクチャ サービスで管理コマンドを非同期的に呼び出します。</para>
        </summary>
        <returns>
          <para>インフラストラクチャ サービスからの応答。 応答の形式は、JSON 文字列です。 応答の内容は、どのコマンドが発行されましたによって異なります。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeInfrastructureQueryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureQueryAsync (Uri serviceName, string command);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureQueryAsync(class System.Uri serviceName, string command) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureQueryAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeInfrastructureQueryAsync (serviceName As Uri, command As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureQueryAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureQueryAsync (serviceName, command)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>対象のインフラストラクチャのサービス インスタンスの名前。</para>
        </param>
        <param name="command">
          <para>呼び出されるコマンドのテキスト。  コマンドのコンテンツは、インフラストラクチャに固有です。</para>
        </param>
        <summary>
          <para>指定されたインフラストラクチャのサービス インスタンスでの読み取り専用クエリを非同期的に呼び出します。</para>
        </summary>
        <returns>
          <para>インフラストラクチャ サービスからの応答。 応答の形式は、JSON 文字列です。 応答の内容は、どのコマンドが発行されましたによって異なります。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeInfrastructureQueryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureQueryAsync (Uri serviceName, string command, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureQueryAsync(class System.Uri serviceName, string command, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureQueryAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureQueryAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureQueryAsync (serviceName, command, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>対象のインフラストラクチャのサービス インスタンスの名前。</para>
        </param>
        <param name="command">
          <para>呼び出されるコマンドのテキスト。  コマンドのコンテンツは、インフラストラクチャに固有です。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>指定されたインフラストラクチャのサービス インスタンスでの読み取り専用クエリを非同期的に呼び出します。</para>
        </summary>
        <returns>
          <para>インフラストラクチャ サービスからの応答。 応答の形式は、JSON 文字列です。 応答の内容は、どのコマンドが発行されましたによって異なります。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>