<Type Name="BatchClient" FullName="Microsoft.Azure.Batch.BatchClient">
  <TypeSignature Language="C#" Value="public class BatchClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchClient extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.BatchClient" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type BatchClient = class&#xA;    interface IDisposable" />
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
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            バッチ サービスにアクセスするために使用して Azure Batch アカウントのクライアントです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ApplicationOperations ApplicationOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ApplicationOperations ApplicationOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.ApplicationOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationOperations As ApplicationOperations" />
      <MemberSignature Language="F#" Value="member this.ApplicationOperations : Microsoft.Azure.Batch.ApplicationOperations" Usage="Microsoft.Azure.Batch.BatchClient.ApplicationOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ApplicationOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="P:Microsoft.Azure.Batch.BatchClient.ApplicationOperations" />関連付けられたアカウントでアプリケーションに関連する操作を実行します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CertificateOperations CertificateOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.CertificateOperations CertificateOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.CertificateOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CertificateOperations As CertificateOperations" />
      <MemberSignature Language="F#" Value="member this.CertificateOperations : Microsoft.Azure.Batch.CertificateOperations" Usage="Microsoft.Azure.Batch.BatchClient.CertificateOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CertificateOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="P:Microsoft.Azure.Batch.BatchClient.CertificateOperations" />関連付けられているアカウントに証明書関連の操作を実行するためです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Close">
      <MemberSignature Language="C#" Value="public void Close ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Close() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Close" />
      <MemberSignature Language="VB.NET" Value="Public Sub Close ()" />
      <MemberSignature Language="F#" Value="member this.Close : unit -&gt; unit" Usage="batchClient.Close " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のインスタンスを閉じます<see cref="T:Microsoft.Azure.Batch.BatchClient" />です。  
            インスタンスを閉じて<see cref="T:Microsoft.Azure.Batch.BatchClient" />Batch Service への呼び出しを行うことができない他のメソッドまたはプロパティの値と動作は未定義とします。 これらの制限もすぐにオブジェクトに適用するトレースをこの厳密<see cref="T:Microsoft.Azure.Batch.BatchClient" />です。
            このメソッドはスレッド セーフであるため、何度でも呼び出すことができます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="batchClient.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のインスタンスを閉じる非同期操作を開始<see cref="T:Microsoft.Azure.Batch.BatchClient" />です。  
            インスタンスを閉じて<see cref="T:Microsoft.Azure.Batch.BatchClient" />Batch Service への呼び出しを行うことができない他のメソッドまたはプロパティの値と動作は未定義とします。 これらの制限もすぐにオブジェクトに適用するトレースをこの厳密<see cref="T:Microsoft.Azure.Batch.BatchClient" />です。
            このメソッドはスレッド セーフであるため、何度でも呼び出すことができます。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.BatchClient.CustomBehaviors" />
      <MemberType>Property</MemberType>
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
            取得または設定を変更または、Batch service への要求をカスタマイズする動作のリスト。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>これらの動作は、子オブジェクトによって継承されます。</para>
          <para>変更は、コレクションの順序で適用されます。 最後には、wins を記述します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="batchClient.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            呼び出し<see cref="M:Microsoft.Azure.Batch.BatchClient.Close" />し、解放、アンマネージ リソースおよびによって使用されているマネージ リソースを破棄、<see cref="T:Microsoft.Azure.Batch.BatchClient" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="batchClient.Dispose disposing" />
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
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">オブジェクトがされているかどうかを示す破棄または終了します。  True の場合、オブジェクトが破棄されると、マネージ リソースを破棄することができます。  False の場合、オブジェクトが終了処理中は、アンマネージ リソースだけを解放する必要があります。</param>
        <summary>
            によって使用されるアンマネージ リソースを解放、 <see cref="T:Microsoft.Azure.Batch.BatchClient" />、必要に応じてマネージ リソースを破棄します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobOperations JobOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobOperations JobOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.JobOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobOperations As JobOperations" />
      <MemberSignature Language="F#" Value="member this.JobOperations : Microsoft.Azure.Batch.JobOperations" Usage="Microsoft.Azure.Batch.BatchClient.JobOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="P:Microsoft.Azure.Batch.BatchClient.JobOperations" />関連付けられたアカウントでのジョブに関連する操作を実行します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobScheduleOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobScheduleOperations JobScheduleOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobScheduleOperations JobScheduleOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.JobScheduleOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobScheduleOperations As JobScheduleOperations" />
      <MemberSignature Language="F#" Value="member this.JobScheduleOperations : Microsoft.Azure.Batch.JobScheduleOperations" Usage="Microsoft.Azure.Batch.BatchClient.JobScheduleOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobScheduleOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="P:Microsoft.Azure.Batch.BatchClient.JobScheduleOperations" />関連付けられたアカウントに対してジョブ スケジュールに関連する操作を実行するためです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.BatchClient Open (Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.BatchClient Open(class Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Open(Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Open (credentials As BatchSharedKeyCredentials) As BatchClient" />
      <MemberSignature Language="F#" Value="static member Open : Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials -&gt; Microsoft.Azure.Batch.BatchClient" Usage="Microsoft.Azure.Batch.BatchClient.Open credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.BatchClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">Batch アカウントの資格情報。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.BatchClient" /> のインスタンスを作成します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" /> のインスタンス。</returns>
        <remarks>
            これは、ブロッキング呼び出しです。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials)" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.BatchClient Open (Microsoft.Azure.Batch.Auth.BatchTokenCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.BatchClient Open(class Microsoft.Azure.Batch.Auth.BatchTokenCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Open(Microsoft.Azure.Batch.Auth.BatchTokenCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Open (credentials As BatchTokenCredentials) As BatchClient" />
      <MemberSignature Language="F#" Value="static member Open : Microsoft.Azure.Batch.Auth.BatchTokenCredentials -&gt; Microsoft.Azure.Batch.BatchClient" Usage="Microsoft.Azure.Batch.BatchClient.Open credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.BatchClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.Batch.Auth.BatchTokenCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">Azure Active Directory Batch アカウントの資格情報。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.BatchClient" /> のインスタンスを作成します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" /> のインスタンス。</returns>
        <remarks>
            これは、ブロッキング呼び出しです。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Auth.BatchTokenCredentials)" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.BatchClient Open (Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.BatchClient Open(class Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Open(Microsoft.Azure.Batch.Protocol.BatchServiceClient)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Open (restClient As BatchServiceClient) As BatchClient" />
      <MemberSignature Language="F#" Value="static member Open : Microsoft.Azure.Batch.Protocol.BatchServiceClient -&gt; Microsoft.Azure.Batch.BatchClient" Usage="Microsoft.Azure.Batch.BatchClient.Open restClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.BatchClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
      </Parameters>
      <Docs>
        <param name="restClient">インスタンス<see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />バッチ サービスに対して行われたすべての呼び出しに使用します。 インスタンスはありません、BatchClient が破棄されるときに破棄されます。</param>
        <summary>
            インスタンスを作成するための呼び出しをブロックして<see cref="T:Microsoft.Azure.Batch.BatchClient" />に指定された関連付けられている<see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />です。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" /> のインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt; OpenAsync (Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.BatchClient&gt; OpenAsync(class Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OpenAsync (credentials As BatchSharedKeyCredentials) As Task(Of BatchClient)" />
      <MemberSignature Language="F#" Value="static member OpenAsync : Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;" Usage="Microsoft.Azure.Batch.BatchClient.OpenAsync credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">Batch アカウントの資格情報。</param>
        <summary>
            インスタンスを作成<see cref="T:Microsoft.Azure.Batch.BatchClient" />指定された資格情報に関連付けられています。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt; OpenAsync (Microsoft.Azure.Batch.Auth.BatchTokenCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.BatchClient&gt; OpenAsync(class Microsoft.Azure.Batch.Auth.BatchTokenCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Auth.BatchTokenCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OpenAsync (credentials As BatchTokenCredentials) As Task(Of BatchClient)" />
      <MemberSignature Language="F#" Value="static member OpenAsync : Microsoft.Azure.Batch.Auth.BatchTokenCredentials -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;" Usage="Microsoft.Azure.Batch.BatchClient.OpenAsync credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.Batch.Auth.BatchTokenCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">Azure Active Directory Batch アカウントの資格情報。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.BatchClient" /> のインスタンスを作成します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt; OpenAsync (Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.BatchClient&gt; OpenAsync(class Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Protocol.BatchServiceClient)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OpenAsync (restClient As BatchServiceClient) As Task(Of BatchClient)" />
      <MemberSignature Language="F#" Value="static member OpenAsync : Microsoft.Azure.Batch.Protocol.BatchServiceClient -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;" Usage="Microsoft.Azure.Batch.BatchClient.OpenAsync restClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
      </Parameters>
      <Docs>
        <param name="restClient">インスタンス<see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />バッチ サービスに対して行われたすべての呼び出しに使用します。 インスタンスはありません、BatchClient が破棄されるときに破棄されます。</param>
        <summary>
            インスタンスを作成<see cref="T:Microsoft.Azure.Batch.BatchClient" />に指定された関連付けられている<see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolOperations PoolOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.PoolOperations PoolOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.PoolOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PoolOperations As PoolOperations" />
      <MemberSignature Language="F#" Value="member this.PoolOperations : Microsoft.Azure.Batch.PoolOperations" Usage="Microsoft.Azure.Batch.BatchClient.PoolOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="P:Microsoft.Azure.Batch.BatchClient.PoolOperations" />関連付けられているアカウントにプール関連の操作を実行するためです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Utilities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Utilities Utilities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Utilities Utilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.Utilities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Utilities As Utilities" />
      <MemberSignature Language="F#" Value="member this.Utilities : Microsoft.Azure.Batch.Utilities" Usage="Microsoft.Azure.Batch.BatchClient.Utilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Utilities</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="P:Microsoft.Azure.Batch.BatchClient.Utilities" />を複数のバッチ操作を調整するためのユーティリティ メソッドを含むオブジェクト。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>