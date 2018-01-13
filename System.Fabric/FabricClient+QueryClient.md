<Type Name="FabricClient+QueryClient" FullName="System.Fabric.FabricClient+QueryClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.QueryClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/QueryClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.QueryClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.QueryClient" />
  <TypeSignature Language="F#" Value="type FabricClient.QueryClient = class" />
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
      <para>クエリを実行するために使用するファブリック クライアントを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationListAsync () As Task(Of ApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            システムで作成されたすべてのアプリケーションの詳細を取得します。 ページで、アプリケーションが収まらない場合は、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>指定されたアプリケーション名が一致するアプリケーションを持たない場合は、エントリ数が 0 の一覧を返します。</para>
          <para>返されたタスクには、としてアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationListAsync (applicationNameFilter As Uri) As Task(Of ApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync applicationNameFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para>詳細を取得するアプリケーションの名前です。</para>
        </param>
        <summary>
          <para>
            すべてのアプリケーションまたはシステムで作成された特定のアプリケーションの詳細を取得します。 ページで、アプリケーションが収まらない場合は、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationList" />です。</para>
          <para>指定されたアプリケーション名が一致するアプリケーションを持たない場合は、エントリ数が 0 の一覧を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationListAsync (applicationNameFilter As Uri, continuationToken As String) As Task(Of ApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync (applicationNameFilter, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para>詳細を取得するアプリケーションの名前です。</para>
        </param>
        <param name="continuationToken">
          <para>前のクエリから取得された継続トークンです。</para>
        </param>
        <summary>
          <para>
            すべてのアプリケーションまたはシステムで作成された特定のアプリケーションの詳細を取得します。 ページで、アプリケーションが収まらない場合は、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationList" />です。</para>
          <para>指定されたアプリケーション名が一致するアプリケーションを持たない場合は、エントリ数が 0 の一覧を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync (applicationNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para>詳細を取得するアプリケーションの名前です。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>
            すべてのアプリケーションまたはシステムで作成された特定のアプリケーションの詳細を取得します。 ページで、アプリケーションが収まらない場合は、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationList" />です。</para>
          <para>指定されたアプリケーション名が一致するアプリケーションを持たない場合は、エントリ数が 0 の一覧を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync (applicationNameFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para>詳細を取得するアプリケーションの名前です。</para>
        </param>
        <param name="continuationToken">
          <para>前のクエリから取得された継続トークンです。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す必要がある通知を伝達します。</para>
        </param>
        <summary>
          <para>
            すべてのアプリケーションまたはシステムで作成された特定のアプリケーションの詳細を取得します。 ページで、アプリケーションが収まらない場合は、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationList" />です。</para>
          <para>指定されたアプリケーション名が一致するアプリケーションを持たない場合は、エントリ数が 0 の一覧を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync (string applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync(string applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationLoadInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationLoadInformationAsync (applicationName As String) As Task(Of ApplicationLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationLoadInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;" Usage="queryClient.GetApplicationLoadInformationAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーション インスタンス名の URI。</para>
        </param>
        <summary>
          <para>指定したアプリケーション インスタンスの読み込み情報を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、アプリケーションの情報が含まれています。<see cref="T:System.Fabric.Query.ApplicationLoadInformation" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync (string applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync(string applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationLoadInformationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationLoadInformationAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;" Usage="queryClient.GetApplicationLoadInformationAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーション インスタンス名の URI。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>指定したアプリケーション インスタンスの読み込み情報を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、アプリケーションの情報が含まれています。<see cref="T:System.Fabric.Query.ApplicationLoadInformation" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしました。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationNameResult&gt; GetApplicationNameAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationNameResult&gt; GetApplicationNameAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationNameAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationNameAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationNameResult&gt;" Usage="queryClient.GetApplicationNameAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationNameResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>アプリケーションの名前を取得するサービスの名前です。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>指定したサービス アプリケーションの名前を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。 </para>
          <para>返されたタスクには、アプリケーション名が含まれています。<see cref="T:System.Fabric.Query.ApplicationNameResult" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationPagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync (System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync(class System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationPagedListAsync(System.Fabric.Description.ApplicationQueryDescription)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationPagedListAsync : System.Fabric.Description.ApplicationQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationPagedListAsync applicationQueryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationQueryDescription" Type="System.Fabric.Description.ApplicationQueryDescription" />
      </Parameters>
      <Docs>
        <param name="applicationQueryDescription">
          <para><see cref="T:System.Fabric.Description.ApplicationQueryDescription" />を決定するアプリケーションのクエリを実行する必要があります。</para>
        </param>
        <summary>
          <para>作成する (存在する場合)、クエリの説明で指定されたフィルターに一致するアプリケーションの詳細を取得します。
            ページで、アプリケーションが収まらない場合は、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。
            TResult のパラメーターの値は、<see cref="T:System.Fabric.Query.ApplicationList" />内のフィルターを適用するアプリケーションの一覧を表す、<see cref="T:System.Fabric.Description.ApplicationQueryDescription" />ページに合わせてとします。
            指定されたクエリの説明に一致するアプリケーションがあるない場合は、エントリ数が 0 の一覧を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationPagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync (System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync(class System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationPagedListAsync(System.Fabric.Description.ApplicationQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationPagedListAsync : System.Fabric.Description.ApplicationQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationPagedListAsync (applicationQueryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationQueryDescription" Type="System.Fabric.Description.ApplicationQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationQueryDescription">
          <para><see cref="T:System.Fabric.Description.ApplicationQueryDescription" />を決定するアプリケーションのクエリを実行する必要があります。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す必要がある通知を伝達します。</para>
        </param>
        <summary>
          <para>作成する (存在する場合)、クエリの説明で指定されたフィルターに一致するアプリケーションの詳細を取得します。
            ページで、アプリケーションが収まらない場合は、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。
            TResult のパラメーターの値は、<see cref="T:System.Fabric.Query.ApplicationList" />内のフィルターを適用するアプリケーションの一覧を表す、<see cref="T:System.Fabric.Description.ApplicationQueryDescription" />ページに合わせてとします。
            指定されたクエリの説明に一致するアプリケーションがあるない場合は、エントリ数が 0 の一覧を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypeListAsync () As Task(Of ApplicationTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypeListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;" Usage="queryClient.GetApplicationTypeListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>すべてのアプリケーションの種類の詳細を取得プロビジョニングまたはシステムでプロビジョニングされています。
            多くの機能を使用してください<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />です。
            このメソッドは、今後廃止される予定です。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてアプリケーションの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationTypeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync (string applicationTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync(string applicationTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypeListAsync (applicationTypeNameFilter As String) As Task(Of ApplicationTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypeListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;" Usage="queryClient.GetApplicationTypeListAsync applicationTypeNameFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeNameFilter">
          <para>サービスの種類を取得するアプリケーションの型名。</para>
        </param>
        <summary>
          <para>すべてのアプリケーションの種類の詳細を取得プロビジョニングまたはシステム、または、指定したアプリケーションの種類にプロビジョニングされています。
            多くの機能を使用してください<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />です。
            このメソッドは、今後廃止される予定です。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてアプリケーションの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationTypeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync (string applicationTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync(string applicationTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypeListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;" Usage="queryClient.GetApplicationTypeListAsync (applicationTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeNameFilter">
          <para>サービスの種類を取得するアプリケーションの型名。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>すべてのアプリケーションの種類の詳細を取得プロビジョニングまたはシステム、または、指定したアプリケーションの種類にプロビジョニングされています。
            多くの機能を使用してください<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />です。
            このメソッドは、今後廃止される予定です。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてアプリケーションの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationTypeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypePagedListAsync () As Task(Of ApplicationTypePagedList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypePagedListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;" Usage="queryClient.GetApplicationTypePagedListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
                    すべてのアプリケーションの種類の詳細を取得プロビジョニングまたはシステムでプロビジョニングされています。 
                </para>
        </summary>
        <returns>
          <para>
                   A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。 TResult のパラメーターの値は、<see cref="T:System.Fabric.Query.ApplicationTypePagedList" />です。
                   </para>
          <para> 
                   アプリケーションの種類が見つからない場合、使用できるフィルターに一致する、このクエリは、エラーではなくアプリケーション型ではなくを返します。
                </para>
        </returns>
        <remarks>
          <para>
                    これをすべてのアプリケーションの種類収まらない場合、ページ内の意味、ページングされたクエリは、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。 たとえば、10000 アプリケーションの種類がありますが、ページでは、最初の 3000 アプリケーションの種類のみに適した、3000 が返されます。
                    残りの結果にアクセスするには、返された継続トークンを次のクエリで使用して、後続のページを取得します。
                    後続のページが存在しない場合は、null の継続トークンが返されます。
                    </para>
          <para>
                    特定のアプリケーションの種類の各バージョンでは、結果内の 1 つのエントリです。
                </para>
        </remarks>
        <remarks>
          <para>
                    ここでのアプリケーションの種類に関する詳細を参照してください:<see cref="T:System.Fabric.Query.ApplicationType" />です。
                </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync (System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync(class System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync(System.Fabric.Description.PagedApplicationTypeQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypePagedListAsync (queryDescription As PagedApplicationTypeQueryDescription) As Task(Of ApplicationTypePagedList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypePagedListAsync : System.Fabric.Description.PagedApplicationTypeQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;" Usage="queryClient.GetApplicationTypePagedListAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.PagedApplicationTypeQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">
          <para>
                    A<see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" />すると、アプリケーションが返される型を記述するオブジェクト。
                    </para>
        </param>
        <summary>
          <para>
                    アプリケーションの種類の詳細のプロビジョニングを取得または queryDescription 引数によって提供されるフィルターに一致するシステムでプロビジョニングされています。
                    </para>
        </summary>
        <returns>
          <para>
                   A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。 TResult のパラメーターの値は、<see cref="T:System.Fabric.Query.ApplicationTypePagedList" />です。
                   </para>
          <para> 
                   アプリケーションの種類が見つからない場合、使用できるフィルターに一致する、このクエリは、エラーではなくアプリケーション型ではなくを返します。
                </para>
        </returns>
        <remarks>
          <para>
                    これをすべてのアプリケーションの種類収まらない場合、ページ内の意味、ページングされたクエリは、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。 たとえば、10000 アプリケーションの種類がありますが、ページでは、最初の 3000 アプリケーションの種類のみに適した、3000 が返されます。
                    残りの結果にアクセスするには、返された継続トークンを次のクエリで使用して、後続のページを取得します。
                    後続のページが存在しない場合は、null の継続トークンが返されます。
                    </para>
          <para>
                    特定のアプリケーションの種類の各バージョンでは、結果内の 1 つのエントリです。
                </para>
        </remarks>
        <remarks>
          <para>
                    ここでのアプリケーションの種類に関する詳細を参照してください:<see cref="T:System.Fabric.Query.ApplicationType" />です。
                </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync (System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync(class System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync(System.Fabric.Description.PagedApplicationTypeQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypePagedListAsync : System.Fabric.Description.PagedApplicationTypeQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;" Usage="queryClient.GetApplicationTypePagedListAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.PagedApplicationTypeQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">
          <para>
                    A<see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" />すると、アプリケーションが返される型を記述するオブジェクト。
                    </para>
        </param>
        <param name="timeout">
          <para>
                    この操作がタイムアウトするまでに完了する必要がある期間を指定します。
                </para>
        </param>
        <param name="cancellationToken">
          <para>
                    操作を取り消す通知を配信します。
                </para>
        </param>
        <summary>
          <para>
                    アプリケーションの種類の詳細のプロビジョニングを取得または queryDescription 引数によって提供されるフィルターに一致するシステムでプロビジョニングされています。
                    </para>
        </summary>
        <returns>
          <para>
                   A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。 TResult のパラメーターの値は、<see cref="T:System.Fabric.Query.ApplicationTypePagedList" />です。
                   </para>
          <para> 
                   アプリケーションの種類が見つからない場合、使用できるフィルターに一致する、このクエリは、エラーではなくアプリケーション型ではなくを返します。
                </para>
        </returns>
        <remarks>
          <para>
                    これをすべてのアプリケーションの種類収まらない場合、ページ内の意味、ページングされたクエリは、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。 たとえば、10000 アプリケーションの種類がありますが、ページでは、最初の 3000 アプリケーションの種類のみに適した、3000 が返されます。
                    残りの結果にアクセスするには、返された継続トークンを次のクエリで使用して、後続のページを取得します。
                    後続のページが存在しない場合は、null の継続トークンが返されます。
                    </para>
          <para>
                    特定のアプリケーションの種類の各バージョンでは、結果内の 1 つのエントリです。
                </para>
        </remarks>
        <remarks>
          <para>
                    ここでのアプリケーションの種類に関する詳細を参照してください:<see cref="T:System.Fabric.Query.ApplicationType" />です。
                </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetClusterLoadInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterLoadInformationAsync () As Task(Of ClusterLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetClusterLoadInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;" Usage="queryClient.GetClusterLoadInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>クラスターの読み込み情報を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>以下を参照してください。<see cref="T:System.Fabric.Query.ClusterLoadInformation" /></para>
          <para>返されたタスクには、としてクラスターの負荷の情報が含まれています。<see cref="T:System.Fabric.Query.ClusterLoadInformation" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetClusterLoadInformationAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterLoadInformationAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;" Usage="queryClient.GetClusterLoadInformationAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>クラスターの読み込み情報を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてクラスターの負荷の情報が含まれています。<see cref="T:System.Fabric.Query.ClusterLoadInformation" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedApplicationListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationListAsync (nodeName As String) As Task(Of DeployedApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;" Usage="queryClient.GetDeployedApplicationListAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>対応アプリケーションを取得するノードの名前です。</para>
        </param>
        <summary>
          <para>展開済みアプリケーションの一覧を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、として配置されているアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedApplicationList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync (string nodeName, Uri applicationNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync(string nodeName, class System.Uri applicationNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedApplicationListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationListAsync (nodeName As String, applicationNameFilter As Uri) As Task(Of DeployedApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;" Usage="queryClient.GetDeployedApplicationListAsync (nodeName, applicationNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>対応アプリケーションを取得するノードの名前です。</para>
        </param>
        <param name="applicationNameFilter">
          <para>このアプリケーションの名前と一致するアプリケーションのみを含める結果をフィルター処理します。</para>
        </param>
        <summary>
          <para>指定したアプリケーション名のノードに展開されたアプリケーションを取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、として配置されているアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedApplicationList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync (string nodeName, Uri applicationNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync(string nodeName, class System.Uri applicationNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedApplicationListAsync(System.String,System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationListAsync : string * Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;" Usage="queryClient.GetDeployedApplicationListAsync (nodeName, applicationNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>対応アプリケーションを取得するノードの名前です。</para>
        </param>
        <param name="applicationNameFilter">
          <para>このアプリケーションの名前と一致するアプリケーションのみを含める結果をフィルター処理します。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>指定したアプリケーション名のノードに展開されたアプリケーションを取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、として配置されているアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedApplicationList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedCodePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedCodePackageListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedCodePackageListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedCodePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedCodePackageListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;" Usage="queryClient.GetDeployedCodePackageListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="applicationName">
          <para>アプリケーションの名前です。</para>
        </param>
        <summary>
          <para>配置されたコード パッケージの一覧を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、として配置されたコード パッケージの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedCodePackageList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedCodePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedCodePackageListAsync(System.String,System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedCodePackageListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String, codePackageNameFilter As String) As Task(Of DeployedCodePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedCodePackageListAsync : string * Uri * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;" Usage="queryClient.GetDeployedCodePackageListAsync (nodeName, applicationName, serviceManifestNameFilter, codePackageNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="codePackageNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="applicationName">
          <para>アプリケーションの名前です。</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>このサービスに一致するもののマニフェスト名だけを含めるようにする結果をフィルター処理します。</para>
        </param>
        <param name="codePackageNameFilter">
          <para>ものだけにこのコード パッケージの名前と一致する結果をフィルター処理します。</para>
        </param>
        <summary>
          <para>配置されたコード パッケージの一覧を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、として配置されたコード パッケージの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedCodePackageList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedCodePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedCodePackageListAsync(System.String,System.Uri,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedCodePackageListAsync : string * Uri * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;" Usage="queryClient.GetDeployedCodePackageListAsync (nodeName, applicationName, serviceManifestNameFilter, codePackageNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="codePackageNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="applicationName">
          <para>アプリケーションの名前です。</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>このサービスに一致するもののマニフェスト名だけを含めるようにする結果をフィルター処理します。</para>
        </param>
        <param name="codePackageNameFilter">
          <para>ものだけにこのコード パッケージの名前と一致する結果をフィルター処理します。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>配置されたコード パッケージの一覧を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、として配置されたコード パッケージの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedCodePackageList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaDetailAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync (string nodeName, Guid partitionId, long replicaId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaDetailAsync (nodeName As String, partitionId As Guid, replicaId As Long) As Task(Of DeployedServiceReplicaDetail)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaDetailAsync : string * Guid * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;" Usage="queryClient.GetDeployedReplicaDetailAsync (nodeName, partitionId, replicaId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>元の結果が必要なノード名です。</para>
        </param>
        <param name="partitionId">
          <para>結果が必要となるパーティションの id です。</para>
        </param>
        <param name="replicaId">
          <para>レプリカまたは結果が必要となるインスタンスの識別子。</para>
        </param>
        <summary>
          <para>指定したノードで実行されているレプリカの詳細を返します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されるタスク、レプリカとして情報を含む<see cref="T:System.Fabric.Query.DeployedServiceReplicaDetail" />です。</para>
        </returns>
        <remarks>
          <para>
                Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。 </para>
          <para>
                このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaDetailAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync (string nodeName, Guid partitionId, long replicaId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaDetailAsync : string * Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;" Usage="queryClient.GetDeployedReplicaDetailAsync (nodeName, partitionId, replicaId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>元の結果が必要なノード名です。</para>
        </param>
        <param name="partitionId">
          <para>結果が必要となるパーティションの id です。</para>
        </param>
        <param name="replicaId">
          <para>レプリカまたは結果が必要となるインスタンスの識別子。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>指定したノードで実行されているレプリカの詳細を返します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されるタスク、レプリカとして情報を含む<see cref="T:System.Fabric.Query.DeployedServiceReplicaDetail" />です。</para>
        </returns>
        <remarks>
          <para>
                Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。 </para>
          <para>
                このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="applicationName">
          <para>アプリケーションの名前です。</para>
        </param>
        <summary>
          <para>ノードからのレプリカのビューを取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されるタスクには、展開済みサービスのレプリカとしての一覧が含まれています<see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />です。</para>
        </returns>
        <remarks>
          <para>
                Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。 </para>
          <para>
                このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName, Nullable&lt;Guid&gt; partitionIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaListAsync (nodeName As String, applicationName As Uri, partitionIdFilter As Nullable(Of Guid)) As Task(Of DeployedServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri * Nullable&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName, partitionIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="applicationName">
          <para>アプリケーションの名前です。</para>
        </param>
        <param name="partitionIdFilter">
          <para>このパーティションの ID に一致するレプリカだけを結果をフィルター処理します。</para>
        </param>
        <summary>
          <para>ノードからのレプリカのビューを取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されるタスクには、展開済みサービスのレプリカとしての一覧が含まれています<see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />です。</para>
        </returns>
        <remarks>
          <para>
                Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。 </para>
          <para>
                このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, Nullable&lt;Guid&gt; partitionIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri,System.String,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String, partitionIdFilter As Nullable(Of Guid)) As Task(Of DeployedServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri * string * Nullable&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName, serviceManifestNameFilter, partitionIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="applicationName">
          <para>アプリケーションの名前です。</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>このサービスに一致するもののマニフェスト名だけを含めるようにする結果をフィルター処理します。</para>
        </param>
        <param name="partitionIdFilter">
          <para>このパーティションの ID に一致するレプリカだけを結果をフィルター処理します。</para>
        </param>
        <summary>
          <para>ノードからのレプリカのビューを取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されるタスクには、展開済みサービスのレプリカとしての一覧が含まれています<see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />です。</para>
        </returns>
        <remarks>
          <para>
                Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。 </para>
          <para>
                このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, Nullable&lt;Guid&gt; partitionIdFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri,System.String,System.Nullable{System.Guid},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri * string * Nullable&lt;Guid&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName, serviceManifestNameFilter, partitionIdFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="applicationName">
          <para>アプリケーションの名前です。</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>このサービスに一致するもののマニフェスト名だけを含めるようにする結果をフィルター処理します。</para>
        </param>
        <param name="partitionIdFilter">
          <para>このパーティションの ID に一致するレプリカだけを結果をフィルター処理します。</para>
        </param>
        <param name="timeout">
          <para>返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>ノードからのレプリカのビューを取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されるタスクには、展開済みサービスのレプリカとしての一覧が含まれています<see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />です。</para>
        </returns>
        <remarks>
          <para>
                Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。 </para>
          <para>
                このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedServicePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;" Usage="queryClient.GetDeployedServicePackageListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="applicationName">
          <para>アプリケーションの名前です。</para>
        </param>
        <summary>
          <para>指定したノードとアプリケーションの展開済みサービス パッケージを取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、パッケージの展開済みサービスの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedServicePackageList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String) As Task(Of DeployedServicePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageListAsync : string * Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;" Usage="queryClient.GetDeployedServicePackageListAsync (nodeName, applicationName, serviceManifestNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="applicationName">
          <para>アプリケーションの名前です。</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>このサービスに一致するもののマニフェスト名だけを含めるようにする結果をフィルター処理します。</para>
        </param>
        <summary>
          <para>指定したノードとアプリケーションの展開済みサービス パッケージを取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、パッケージの展開済みサービスの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedServicePackageList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageListAsync : string * Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;" Usage="queryClient.GetDeployedServicePackageListAsync (nodeName, applicationName, serviceManifestNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="applicationName">
          <para>アプリケーションの名前です。</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>このサービスに一致するもののマニフェスト名だけを含めるようにする結果をフィルター処理します。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>指定したノードとアプリケーションの展開済みサービス パッケージを取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、パッケージの展開済みサービスの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedServicePackageList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServiceTypeListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServiceTypeListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServiceTypeListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;" Usage="queryClient.GetDeployedServiceTypeListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="applicationName">
          <para>アプリケーションの名前です。</para>
        </param>
        <summary>
          <para>指定したノードとアプリケーションの展開済みサービスの種類を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、として展開されているサービスの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedServiceTypeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServiceTypeListAsync(System.String,System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServiceTypeListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String, serviceTypeNameFilter As String) As Task(Of DeployedServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServiceTypeListAsync : string * Uri * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;" Usage="queryClient.GetDeployedServiceTypeListAsync (nodeName, applicationName, serviceManifestNameFilter, serviceTypeNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="applicationName">
          <para>アプリケーションの名前です。</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>このサービス マニフェスト名と一致するサービス型のみを含めるための結果をフィルター処理します。</para>
        </param>
        <param name="serviceTypeNameFilter">
          <para>この名前に一致するサービス型のみを含めるための結果をフィルター処理します。</para>
        </param>
        <summary>
          <para>指定したノードとアプリケーションの展開済みサービスの種類を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、として展開されているサービスの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedServiceTypeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServiceTypeListAsync(System.String,System.Uri,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServiceTypeListAsync : string * Uri * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;" Usage="queryClient.GetDeployedServiceTypeListAsync (nodeName, applicationName, serviceManifestNameFilter, serviceTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="applicationName">
          <para>アプリケーションの名前です。</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>このサービス マニフェスト名と一致するサービス型のみを含めるための結果をフィルター処理します。</para>
        </param>
        <param name="serviceTypeNameFilter">
          <para>この名前に一致するサービス型のみを含めるための結果をフィルター処理します。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>指定したノードとアプリケーションの展開済みサービスの種類を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、として展開されているサービスの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedServiceTypeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeListAsync () As Task(Of NodeList)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            クラスター内のすべてのノードの詳細を取得します。 ページ内のノードが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてノードの一覧が含まれています。<see cref="T:System.Fabric.Query.NodeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeListAsync (nodeNameFilter As String) As Task(Of NodeList)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync nodeNameFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para>詳細を取得するノードの名前です。 ノード名は区別されません。 指定したノード名が null の場合は、クラスター内のすべてのノードを取得します。</para>
        </param>
        <summary>
          <para>
            クラスター内のすべてのノードのまたは指定したノードに対しては、詳細を取得します。 ページ内のノードが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてノードの一覧が含まれています。<see cref="T:System.Fabric.Query.NodeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeListAsync (nodeNameFilter As String, continuationToken As String) As Task(Of NodeList)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para>詳細を取得するノードの名前です。 ノード名は区別されません。 指定したノード名が null の場合は、すべてのノードを取得します。</para>
        </param>
        <param name="continuationToken">
          <para>前のクエリから取得された継続トークンです。</para>
          <returns>
            <para>非同期クエリ操作を表すタスク。</para>
            <para>返されたタスクには、としてノードの一覧が含まれています。<see cref="T:System.Fabric.Query.NodeList" />です。</para>
          </returns>
        </param>
        <summary>
          <para>
            クラスター内のすべてのノードのまたは指定したノードに対しては、詳細を取得します。 ページ内のノードが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para>詳細を取得するノードの名前です。 ノード名は区別されません。 指定したノード名が null の場合は、すべてのノードを取得します。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>
            クラスター内のすべてのノードのまたは指定したノードに対しては、詳細を取得します。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてノードの一覧が含まれています。<see cref="T:System.Fabric.Query.NodeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para>詳細を取得するノードの名前です。 ノード名は区別されません。 指定したノード名が null の場合は、すべてのノードを取得します。</para>
        </param>
        <param name="continuationToken">
          <para>前のクエリから取得された継続トークンです。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す必要がある通知を伝達します。</para>
        </param>
        <summary>
          <para>
            クラスター内のすべてのノードのまたは指定したノードに対しては、詳細を取得します。 ページ内のノードが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
          <para>返されたタスクには、としてノードの一覧が含まれています。<see cref="T:System.Fabric.Query.NodeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, System.Fabric.Query.NodeStatusFilter nodeStatusFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, valuetype System.Fabric.Query.NodeStatusFilter nodeStatusFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.Fabric.Query.NodeStatusFilter,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * System.Fabric.Query.NodeStatusFilter * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, nodeStatusFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="nodeStatusFilter" Type="System.Fabric.Query.NodeStatusFilter" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para>詳細を取得するノードの名前です。 ノード名は区別されません。 指定したノード名が null の場合は、すべてのノードを取得します。</para>
        </param>
        <param name="nodeStatusFilter">
          <para>詳細を取得するノードのノードの性状態です。</para>
        </param>
        <param name="continuationToken">前のクエリから取得された継続トークンです。</param>
        <param name="timeout">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</param>
        <param name="cancellationToken">操作を取り消す必要がある通知を伝達します。</param>
        <summary>
            クラスター内のすべてのノードのまたは指定したノードに対しては、詳細を取得します。 ページ内のノードが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
          <para>返されたタスクには、としてノードの一覧が含まれています。<see cref="T:System.Fabric.Query.NodeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeLoadInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeLoadInformationAsync (nodeName As String) As Task(Of NodeLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetNodeLoadInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;" Usage="queryClient.GetNodeLoadInformationAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <summary>
          <para>メトリックを取得し、ノードに関する情報を読み込みます。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、ノードの読み込み情報が含まれています。<see cref="T:System.Fabric.Query.NodeLoadInformation" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync (string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync(string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeLoadInformationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeLoadInformationAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;" Usage="queryClient.GetNodeLoadInformationAsync (nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す必要がある通知を伝達します。</para>
        </param>
        <summary>
          <para>メトリックを取得し、ノードに関する情報を読み込みます。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、ノードの読み込み情報が含まれています。<see cref="T:System.Fabric.Query.NodeLoadInformation" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionAsync (partitionId As Guid) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>詳細を取得するパーティションのパーティション ID。</para>
        </param>
        <summary>
          <para>
            指定したパーティションの詳細を取得します。
            </para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
          <para>返されたタスクには、としてパーティションの一覧が含まれています。<see cref="T:System.Fabric.Query.ServicePartitionList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>詳細を取得するパーティションのパーティション ID。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す必要がある通知を伝達します。</para>
        </param>
        <summary>
          <para>
            指定したパーティションの詳細を取得します。
            </para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
          <para>返されたタスクには、としてパーティションの一覧が含まれています。<see cref="T:System.Fabric.Query.ServicePartitionList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionListAsync (serviceName As Uri) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>用のパーティションを取得するサービスの名前です。</para>
        </param>
        <summary>
          <para>
            サービスのすべてのパーティションの詳細を取得します。 パーティションは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてパーティションの一覧が含まれています。<see cref="T:System.Fabric.Query.ServicePartitionList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, Nullable&lt;Guid&gt; partitionIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionListAsync (serviceName As Uri, partitionIdFilter As Nullable(Of Guid)) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * Nullable&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, partitionIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスの名前。</para>
        </param>
        <param name="partitionIdFilter">
          <para>詳細を取得するパーティションのパーティション ID。</para>
        </param>
        <summary>
          <para>
            サービスのすべてのパーティションまたは指定されたパーティションのみの詳細を取得します。 パーティションは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてパーティションの一覧が含まれています。<see cref="T:System.Fabric.Query.ServicePartitionList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionListAsync (serviceName As Uri, continuationToken As String) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスの名前。</para>
        </param>
        <param name="continuationToken">
          <para>前のクエリから取得された継続トークンです。</para>
        </param>
        <summary>
          <para>
            サービスのすべてのパーティションの詳細を取得します。 パーティションは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
          <para>返されたタスクには、としてパーティションの一覧が含まれています。<see cref="T:System.Fabric.Query.ServicePartitionList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, Nullable&lt;Guid&gt; partitionIdFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.Nullable{System.Guid},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * Nullable&lt;Guid&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, partitionIdFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスの名前。</para>
        </param>
        <param name="partitionIdFilter">
          <para>詳細を取得するパーティションのパーティション ID。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>
            サービスのすべてのパーティションまたは指定されたパーティションのみの詳細を取得します。 パーティションは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてパーティションの一覧が含まれています。<see cref="T:System.Fabric.Query.ServicePartitionList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, Nullable&lt;Guid&gt; partitionIdFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.Nullable{System.Guid},System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * Nullable&lt;Guid&gt; * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, partitionIdFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスの名前。</para>
        </param>
        <param name="partitionIdFilter">
          <para>詳細を取得するパーティションのパーティション ID。</para>
        </param>
        <param name="continuationToken">
          <para>前のクエリから取得された継続トークンです。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す必要がある通知を伝達します。</para>
        </param>
        <summary>
          <para>
            サービスのすべてのパーティションまたは指定されたパーティションのみの詳細を取得します。 パーティションは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
          <para>返されたタスクには、としてパーティションの一覧が含まれています。<see cref="T:System.Fabric.Query.ServicePartitionList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionLoadInformationAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionLoadInformationAsync (partitionId As Guid) As Task(Of PartitionLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionLoadInformationAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;" Usage="queryClient.GetPartitionLoadInformationAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>負荷の情報を取得する、パーティションのパーティション ID。</para>
        </param>
        <summary>
          <para>パーティションの読み込みに関する情報を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクとパーティションの読み込み情報が含まれています。<see cref="T:System.Fabric.Query.PartitionLoadInformation" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionLoadInformationAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionLoadInformationAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;" Usage="queryClient.GetPartitionLoadInformationAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>負荷の情報を取得する、パーティションのパーティション ID。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>パーティションの読み込みに関する情報を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクとパーティションの読み込み情報が含まれています。<see cref="T:System.Fabric.Query.PartitionLoadInformation" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricCodeVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricCodeVersionListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricCodeVersionListAsync () As Task(Of ProvisionedFabricCodeVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricCodeVersionListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;" Usage="queryClient.GetProvisionedFabricCodeVersionListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>システムでプロビジョニングされたすべてのクラスター コード バージョンの詳細を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、プロビジョニング済みの Service Fabric コード バージョンとしての一覧が含まれています。<see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricCodeVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync (string codeVersionFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync(string codeVersionFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricCodeVersionListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricCodeVersionListAsync (codeVersionFilter As String) As Task(Of ProvisionedFabricCodeVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricCodeVersionListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;" Usage="queryClient.GetProvisionedFabricCodeVersionListAsync codeVersionFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codeVersionFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codeVersionFilter">
          <para>詳細を取得するコードのバージョン。</para>
        </param>
        <summary>
          <para>特定のクラスター コードのバージョンが、システムでプロビジョニングの詳細を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、プロビジョニング済みの Service Fabric コード バージョンとしての一覧が含まれています。<see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricCodeVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync (string codeVersionFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync(string codeVersionFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricCodeVersionListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricCodeVersionListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;" Usage="queryClient.GetProvisionedFabricCodeVersionListAsync (codeVersionFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codeVersionFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="codeVersionFilter">
          <para>コードのバージョンの詳細を取得します。</para>
        </param>
        <param name="timeout">
          <para>TimeoutException がスローされる前に完了する操作にできる最長時間。</para>
        </param>
        <param name="cancellationToken">
          <para>将来使用するために予約されています。</para>
        </param>
        <summary>
          <para>特定のクラスター コードのバージョンが、システムでプロビジョニングの詳細を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、プロビジョニング済みの Service Fabric コード バージョンとしての一覧が含まれています。<see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricConfigVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricConfigVersionListAsync () As Task(Of ProvisionedFabricConfigVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricConfigVersionListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;" Usage="queryClient.GetProvisionedFabricConfigVersionListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>システムでプロビジョニングされたすべてのクラスター構成バージョンの詳細を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてプロビジョニング済みの Service Fabric config のバージョンの一覧が含まれています。<see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricConfigVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync (string configVersionFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync(string configVersionFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricConfigVersionListAsync (configVersionFilter As String) As Task(Of ProvisionedFabricConfigVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricConfigVersionListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;" Usage="queryClient.GetProvisionedFabricConfigVersionListAsync configVersionFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configVersionFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configVersionFilter">
          <para>Config のバージョンの詳細を取得します。</para>
        </param>
        <summary>
          <para>システムでプロビジョニングされた特定のクラスター構成のバージョンの詳細を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてプロビジョニング済みの Service Fabric config のバージョンの一覧が含まれています。<see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricConfigVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync (string configVersionFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync(string configVersionFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricConfigVersionListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;" Usage="queryClient.GetProvisionedFabricConfigVersionListAsync (configVersionFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configVersionFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configVersionFilter">
          <para>Config のバージョンの詳細を取得します。</para>
        </param>
        <param name="timeout">
          <para>TimeoutException がスローされる前に完了する操作にできる最長時間。</para>
        </param>
        <param name="cancellationToken">
          <para>将来使用するために予約されています。</para>
        </param>
        <summary>
          <para>システムでプロビジョニングされた特定のクラスター構成のバージョンの詳細を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてプロビジョニング済みの Service Fabric config のバージョンの一覧が含まれています。<see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaListAsync (partitionId As Guid) As Task(Of ServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>レプリカを取得するパーティションのパーティション識別子です。</para>
        </param>
        <summary>
          <para>
            パーティションのすべてのレプリカの詳細を取得します。 ページで、レプリカが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、として、パーティションのレプリカ情報が含まれています。<see cref="T:System.Fabric.Query.ServiceReplicaList" />です。</para>
        </returns>
        <remarks>
          <para>
                Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。 </para>
          <para>
                このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaListAsync (partitionId As Guid, replicaIdOrInstanceIdFilter As Long) As Task(Of ServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>レプリカを取得するパーティションのパーティション識別子です。</para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para>レプリカ識別子またはインスタンス識別子のレプリカを取得します。</para>
        </param>
        <summary>
          <para>
            パーティションのレプリカまたはインスタンスのフィルターおよびステータス フィルターに一致するすべてのレプリカの詳細を取得します。 ページで、レプリカが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、として、パーティションのレプリカ情報が含まれています。<see cref="T:System.Fabric.Query.ServiceReplicaList" />です。</para>
        </returns>
        <remarks>
          <para>
                Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。 </para>
          <para>
                このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaListAsync (partitionId As Guid, continuationToken As String) As Task(Of ServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>レプリカを取得するパーティションのパーティション識別子です。</para>
        </param>
        <param name="continuationToken">
          <para>前のクエリから取得された継続トークンです。</para>
        </param>
        <summary>
          <para>
            パーティションのすべてのレプリカの詳細を取得します。 ページで、レプリカが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
          <para>返されたタスクには、として、パーティションのレプリカ情報が含まれています。<see cref="T:System.Fabric.Query.ServiceReplicaList" />です。</para>
        </returns>
        <remarks>
          <para>
                Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。 </para>
          <para>
                このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>レプリカを取得するパーティションのパーティション識別子です。</para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para>レプリカ識別子またはインスタンス識別子のレプリカを取得します。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>
            パーティションのレプリカまたはインスタンスのフィルターに一致するすべてのレプリカの詳細を取得します。 ページで、レプリカが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、として、パーティションのレプリカ情報が含まれています。<see cref="T:System.Fabric.Query.ServiceReplicaList" />です。</para>
        </returns>
        <remarks>
          <para>
                Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。 </para>
          <para>
                このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>レプリカを取得するパーティションのパーティション識別子です。</para>
        </param>
        <param name="continuationToken">
          <para>前のクエリから取得された継続トークンです。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す必要がある通知を伝達します。</para>
        </param>
        <summary>
          <para>
            パーティションのすべてのレプリカの詳細を取得します。 ページで、レプリカが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
          <para>返されたタスクには、として、パーティションのレプリカ情報が含まれています。<see cref="T:System.Fabric.Query.ServiceReplicaList" />です。</para>
        </returns>
        <remarks>
          <para>
                Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。 </para>
          <para>
                このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter, System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter, valuetype System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64,System.Fabric.Query.ServiceReplicaStatusFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 * System.Fabric.Query.ServiceReplicaStatusFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter, replicaStatusFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
        <Parameter Name="replicaStatusFilter" Type="System.Fabric.Query.ServiceReplicaStatusFilter" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>レプリカを取得するパーティションのパーティション識別子です。</para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para>レプリカ識別子またはインスタンス識別子のレプリカを取得します。</para>
        </param>
        <param name="replicaStatusFilter">
          <para>レプリカを取得するレプリカ性状態です。</para>
        </param>
        <param name="timeout">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</param>
        <param name="cancellationToken">操作を取り消す必要がある通知を伝達します。</param>
        <summary>
          <para>
            パーティションのレプリカまたはインスタンスのフィルターおよびステータス フィルターに一致するすべてのレプリカの詳細を取得します。 ページで、レプリカが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、として、パーティションのレプリカ情報が含まれています。<see cref="T:System.Fabric.Query.ServiceReplicaList" />です。</para>
        </returns>
        <remarks>
          <para>
                Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。 </para>
          <para>
                このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter, System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter, valuetype System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64,System.Fabric.Query.ServiceReplicaStatusFilter,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 * System.Fabric.Query.ServiceReplicaStatusFilter * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter, replicaStatusFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
        <Parameter Name="replicaStatusFilter" Type="System.Fabric.Query.ServiceReplicaStatusFilter" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>レプリカを取得するパーティションのパーティション識別子です。</para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para>レプリカ識別子またはインスタンス識別子のレプリカを取得します。</para>
        </param>
        <param name="replicaStatusFilter">
          <para>ものだけにこのレプリカの状態に一致する結果をフィルター処理します。</para>
        </param>
        <param name="continuationToken">前のクエリから取得された継続トークンです。</param>
        <param name="timeout">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</param>
        <param name="cancellationToken">操作を取り消す必要がある通知を伝達します。</param>
        <summary>
          <para>
            パーティションのレプリカまたはインスタンスのフィルターおよびステータス フィルターに一致するすべてのレプリカの詳細を取得します。 ページで、レプリカが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、として、パーティションのレプリカ情報が含まれています。<see cref="T:System.Fabric.Query.ServiceReplicaList" />です。</para>
        </returns>
        <remarks>
          <para>
                Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。 </para>
          <para>
                このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync (Guid partitionId, long replicaIdOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaLoadInformationAsync(System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaLoadInformationAsync (partitionId As Guid, replicaIdOrInstanceId As Long) As Task(Of ReplicaLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaLoadInformationAsync : Guid * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;" Usage="queryClient.GetReplicaLoadInformationAsync (partitionId, replicaIdOrInstanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>パーティションの id。</para>
        </param>
        <param name="replicaIdOrInstanceId">
          <para>レプリカ ID (ステートフル サービス) または (ステートレス サービス) のインスタンス ID。</para>
        </param>
        <summary>
          <para>レプリカ上のメトリックとその負荷の一覧を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクと、レプリカの読み込み情報が含まれています。<see cref="T:System.Fabric.Query.ReplicaLoadInformation" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync (Guid partitionId, long replicaIdOrInstanceId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaLoadInformationAsync(System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaLoadInformationAsync : Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;" Usage="queryClient.GetReplicaLoadInformationAsync (partitionId, replicaIdOrInstanceId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>パーティションの id。</para>
        </param>
        <param name="replicaIdOrInstanceId">
          <para>レプリカ ID (ステートフル サービス) または (ステートレス サービス) のインスタンス ID。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>レプリカ上のメトリックとその負荷の一覧を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクと、レプリカの読み込み情報が含まれています。<see cref="T:System.Fabric.Query.ReplicaLoadInformation" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberListAsync (applicationName As Uri) As Task(Of ServiceGroupMemberList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;" Usage="queryClient.GetServiceGroupMemberListAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>サービス グループのアプリケーションの名前。</para>
        </param>
        <summary>
          <para>アプリケーションのサービス グループのメンバーを取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、サービス グループのメンバーとしての一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceGroupMemberList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync (Uri applicationName, Uri serviceNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberListAsync(System.Uri,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberListAsync (applicationName As Uri, serviceNameFilter As Uri) As Task(Of ServiceGroupMemberList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberListAsync : Uri * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;" Usage="queryClient.GetServiceGroupMemberListAsync (applicationName, serviceNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>サービス グループのアプリケーションの名前。</para>
        </param>
        <param name="serviceNameFilter">
          <para>サービス グループのサービス名。</para>
        </param>
        <summary>
          <para>アプリケーションのサービス グループのメンバーを取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、サービス グループのメンバーとしての一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceGroupMemberList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync (Uri applicationName, Uri serviceNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberListAsync(System.Uri,System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberListAsync : Uri * Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;" Usage="queryClient.GetServiceGroupMemberListAsync (applicationName, serviceNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>サービス グループのアプリケーションの名前。</para>
        </param>
        <param name="serviceNameFilter">
          <para>サービス グループのサービス名。</para>
        </param>
        <param name="timeout">
          <para>操作をタイムアウトしました。</para>
        </param>
        <param name="cancellationToken">
          <para>操作をキャンセルするかを通知します。</para>
        </param>
        <summary>
          <para>
            サービスのすべてのパーティションの詳細を取得します。 パーティションは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、サービス グループのメンバーとしての一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceGroupMemberList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberTypeListAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberTypeListAsync (applicationTypeName As String, applicationTypeVersion As String) As Task(Of ServiceGroupMemberTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberTypeListAsync : string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;" Usage="queryClient.GetServiceGroupMemberTypeListAsync (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>サービス グループのアプリケーションの種類の名前。</para>
        </param>
        <param name="applicationTypeVersion">
          <para>サービス グループのアプリケーション タイプのバージョン。</para>
        </param>
        <summary>
          <para>サービス グループ メンバーのサービス グループの種類を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、サービスとしてのグループ メンバーの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberTypeListAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberTypeListAsync (applicationTypeName As String, applicationTypeVersion As String, serviceGroupTypeNameFilter As String) As Task(Of ServiceGroupMemberTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberTypeListAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;" Usage="queryClient.GetServiceGroupMemberTypeListAsync (applicationTypeName, applicationTypeVersion, serviceGroupTypeNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceGroupTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>サービス グループのアプリケーションの種類の名前。</para>
        </param>
        <param name="applicationTypeVersion">
          <para>サービス グループのアプリケーション タイプのバージョン。</para>
        </param>
        <param name="serviceGroupTypeNameFilter">
          <para>取得するサービスのグループの種類の名前。</para>
        </param>
        <summary>
          <para>サービス グループ メンバーのサービス グループの種類を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、サービスとしてのグループ メンバーの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberTypeListAsync(System.String,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberTypeListAsync : string * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;" Usage="queryClient.GetServiceGroupMemberTypeListAsync (applicationTypeName, applicationTypeVersion, serviceGroupTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceGroupTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>サービス グループのアプリケーションの種類の名前。</para>
        </param>
        <param name="applicationTypeVersion">
          <para>サービス グループのアプリケーション タイプのバージョン。</para>
        </param>
        <param name="serviceGroupTypeNameFilter">
          <para>取得するサービスのグループの種類の名前。</para>
        </param>
        <param name="timeout">
          <para>操作をタイムアウトしました。</para>
        </param>
        <param name="cancellationToken">
          <para>操作をキャンセルするかを通知します。</para>
        </param>
        <summary>
          <para>サービス グループ メンバーのサービス グループの種類を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、サービスとしてのグループ メンバーの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceListAsync (applicationName As Uri) As Task(Of ServiceList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>サービスを取得するアプリケーションの名前。</para>
        </param>
        <summary>
          <para>
            アプリケーションの名前 URI で指定されたアプリケーションに属するすべてのサービスに関する情報を取得します。 サービスは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されるタスクには、サービスとしての一覧が含まれています<see cref="T:System.Fabric.Query.ServiceList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceListAsync (applicationName As Uri, serviceNameFilter As Uri) As Task(Of ServiceList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>サービスを取得するアプリケーションの名前。</para>
        </param>
        <param name="serviceNameFilter">
          <para>詳細を取得するサービスの名前です。</para>
        </param>
        <summary>
          <para>
            アプリケーションのすべてのサービスまたは指定したサービスだけの詳細を取得します。 サービスは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されるタスクには、サービスとしての一覧が含まれています<see cref="T:System.Fabric.Query.ServiceList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceListAsync (applicationName As Uri, serviceNameFilter As Uri, continuationToken As String) As Task(Of ServiceList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>サービスを取得するアプリケーションの名前。</para>
        </param>
        <param name="serviceNameFilter">
          <para>詳細を取得するサービスの名前です。</para>
        </param>
        <param name="continuationToken">
          <para>前のクエリから取得された継続トークンです。</para>
        </param>
        <summary>
          <para>
            アプリケーションのすべてのサービスまたは指定したサービスだけの詳細を取得します。 サービスは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
          <para>返されるタスクには、サービスとしての一覧が含まれています<see cref="T:System.Fabric.Query.ServiceList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>サービスを取得するアプリケーションの名前。</para>
        </param>
        <param name="serviceNameFilter">
          <para>詳細を取得するサービスの名前です。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>
            アプリケーションのすべてのサービスまたは指定したサービスだけの詳細を取得します。 サービスは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されるタスクには、サービスとしての一覧が含まれています<see cref="T:System.Fabric.Query.ServiceList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>サービスを取得するアプリケーションの名前。</para>
        </param>
        <param name="serviceNameFilter">
          <para>詳細を取得するサービスの名前です。</para>
        </param>
        <param name="continuationToken">
          <para>前のクエリから取得された継続トークンです。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す必要がある通知を伝達します。</para>
        </param>
        <summary>
          <para>
            アプリケーションのすべてのサービスまたは指定したサービスだけの詳細を取得します。 サービスは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。
            </para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
          <para>返されるタスクには、サービスとしての一覧が含まれています<see cref="T:System.Fabric.Query.ServiceList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceNameResult&gt; GetServiceNameAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceNameResult&gt; GetServiceNameAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceNameAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceNameAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceNameResult&gt;" Usage="queryClient.GetServiceNameAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceNameResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>サービス名を取得するパーティションの id。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>指定したパーティションのサービス名を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、として、サービス名が含まれています。<see cref="T:System.Fabric.Query.ServiceNameResult" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServicePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync (System.Fabric.Description.ServiceQueryDescription serviceQueryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync(class System.Fabric.Description.ServiceQueryDescription serviceQueryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServicePagedListAsync(System.Fabric.Description.ServiceQueryDescription)" />
      <MemberSignature Language="F#" Value="member this.GetServicePagedListAsync : System.Fabric.Description.ServiceQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServicePagedListAsync serviceQueryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceQueryDescription" Type="System.Fabric.Description.ServiceQueryDescription" />
      </Parameters>
      <Docs>
        <param name="serviceQueryDescription">
          <para><see cref="T:System.Fabric.Description.ServiceQueryDescription" />を決定するどのサービスを照会する必要があります。</para>
        </param>
        <summary>
          <para>アプリケーションのすべてのサービスまたは (指定されている場合)、クエリの説明で指定されたフィルターに一致する指定したサービスだけの詳細を取得します。 サービスは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。 TResult のパラメーターの値は、<see cref="T:System.Fabric.Query.ServiceList" />内のフィルターを適用するサービスの一覧を表す、<see cref="T:System.Fabric.Query.ServiceList" />ページに合わせてとします。
            指定されたクエリの説明に一致するサービスがあるない場合は、エントリ数が 0 の一覧を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServicePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync (System.Fabric.Description.ServiceQueryDescription serviceQueryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync(class System.Fabric.Description.ServiceQueryDescription serviceQueryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServicePagedListAsync(System.Fabric.Description.ServiceQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServicePagedListAsync : System.Fabric.Description.ServiceQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServicePagedListAsync (serviceQueryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceQueryDescription" Type="System.Fabric.Description.ServiceQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceQueryDescription">
          <para><see cref="T:System.Fabric.Description.ServiceQueryDescription" />を決定するどのサービスを照会する必要があります。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す必要がある通知を伝達します。</para>
        </param>
        <summary>
          <para>アプリケーションのすべてのサービスまたは (指定されている場合)、クエリの説明で指定されたフィルターに一致する指定したサービスだけの詳細を取得します。 サービスは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。 TResult のパラメーターの値は、<see cref="T:System.Fabric.Query.ServiceList" />内のフィルターを適用するサービスの一覧を表す、<see cref="T:System.Fabric.Query.ServiceList" />ページに合わせてとします。
            指定されたクエリの説明に一致するサービスがあるない場合は、エントリ数が 0 の一覧を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceTypeListAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceTypeListAsync (applicationTypeName As String, applicationTypeVersion As String) As Task(Of ServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceTypeListAsync : string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;" Usage="queryClient.GetServiceTypeListAsync (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>サービスの種類を取得するアプリケーションの型名。</para>
        </param>
        <param name="applicationTypeVersion">
          <para>アプリケーション タイプのバージョンのサービス型を取得するには。</para>
        </param>
        <summary>
          <para>サービスの種類の一覧を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてサービスの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceTypeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceTypeListAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceTypeListAsync (applicationTypeName As String, applicationTypeVersion As String, serviceTypeNameFilter As String) As Task(Of ServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceTypeListAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;" Usage="queryClient.GetServiceTypeListAsync (applicationTypeName, applicationTypeVersion, serviceTypeNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>サービスの種類を取得するアプリケーションの型名。</para>
        </param>
        <param name="applicationTypeVersion">
          <para>アプリケーション タイプのバージョンのサービス型を取得するには。</para>
        </param>
        <param name="serviceTypeNameFilter">
          <para>詳細を取得するサービスの種類の名前。</para>
        </param>
        <summary>
          <para>サービスの種類の一覧を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてサービスの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceTypeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceTypeListAsync(System.String,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceTypeListAsync : string * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;" Usage="queryClient.GetServiceTypeListAsync (applicationTypeName, applicationTypeVersion, serviceTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>サービスの種類を取得するアプリケーションの型名。</para>
        </param>
        <param name="applicationTypeVersion">
          <para>アプリケーション タイプのバージョンのサービス型を取得するには。</para>
        </param>
        <param name="serviceTypeNameFilter">
          <para>詳細を取得するサービスの種類の名前。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>サービスの種類の一覧を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクには、としてサービスの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceTypeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetUnplacedReplicaInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync (string serviceName, Guid partitionId, bool onlyQueryPrimaries);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync(string serviceName, valuetype System.Guid partitionId, bool onlyQueryPrimaries) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetUnplacedReplicaInformationAsync(System.String,System.Guid,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUnplacedReplicaInformationAsync (serviceName As String, partitionId As Guid, onlyQueryPrimaries As Boolean) As Task(Of UnplacedReplicaInformation)" />
      <MemberSignature Language="F#" Value="member this.GetUnplacedReplicaInformationAsync : string * Guid * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;" Usage="queryClient.GetUnplacedReplicaInformationAsync (serviceName, partitionId, onlyQueryPrimaries)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="onlyQueryPrimaries" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスの名前。</para>
        </param>
        <param name="partitionId">
          <para>パーティションの id。</para>
        </param>
        <param name="onlyQueryPrimaries">
          <para>出力を制限するためにのみ、unplaced レプリカの診断を実行しようとしたプライマリ レプリカの配置のみを返します。</para>
        </param>
        <summary>
          <para>Unplaced レプリカとサービスに関する診断情報を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクが未配置レプリカとしての情報を含む<see cref="T:System.Fabric.Query.UnplacedReplicaInformation" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作では、60 秒のタイムアウトがあります。</para>
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetUnplacedReplicaInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync (string serviceName, Guid partitionId, bool onlyQueryPrimaries, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync(string serviceName, valuetype System.Guid partitionId, bool onlyQueryPrimaries, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetUnplacedReplicaInformationAsync(System.String,System.Guid,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetUnplacedReplicaInformationAsync : string * Guid * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;" Usage="queryClient.GetUnplacedReplicaInformationAsync (serviceName, partitionId, onlyQueryPrimaries, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="onlyQueryPrimaries" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスの名前。</para>
        </param>
        <param name="partitionId">
          <para>パーティションの id。</para>
        </param>
        <param name="onlyQueryPrimaries">
          <para>出力を制限するためにのみ、unplaced レプリカの診断を実行しようとしたプライマリ レプリカの配置のみを返します。</para>
        </param>
        <param name="timeout">
          <para>この操作がタイムアウトするまでに完了する必要がある期間を指定します。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を取り消す通知を配信します。</para>
        </param>
        <summary>
          <para>Unplaced レプリカとサービスに関する診断情報を取得します。</para>
        </summary>
        <returns>
          <para>非同期クエリ操作を表すタスク。</para>
          <para>返されたタスクが未配置レプリカとしての情報を含む<see cref="T:System.Fabric.Query.UnplacedReplicaInformation" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>