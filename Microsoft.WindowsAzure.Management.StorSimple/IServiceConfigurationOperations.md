<Type Name="IServiceConfigurationOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations">
  <TypeSignature Language="C#" Value="public interface IServiceConfigurationOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceConfigurationOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceConfigurationOperations" />
  <TypeSignature Language="F#" Value="type IServiceConfigurationOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            サービス構成に関連するすべての操作
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreatingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingAsync (Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingAsync(class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.BeginCreatingAsync(Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreatingAsync : Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iServiceConfigurationOperations.BeginCreatingAsync (serviceConfiguration, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceConfiguration" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceConfiguration">
            パラメーターは、ストレージ アカウントの作成を開始操作に指定します。
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ストレージ アカウントの作成を開始操作は、Azure で新しいストレージ アカウントを作成します。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iServiceConfigurationOperations.CreateAsync (serviceConfiguration, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceConfiguration" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceConfiguration">
            パラメーターは、ストレージ アカウントの作成操作に指定します。
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>To be added.</summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt; GetAsync (Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customeRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customeRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt;" Usage="iServiceConfigurationOperations.GetAsync (customeRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customeRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customeRequestHeaders">To be added.</param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>To be added.</summary>
        <returns>
            そのリソースに関するサービスの構成についての情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>