<Type Name="TransferContext" FullName="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext">
  <TypeSignature Language="C#" Value="public abstract class TransferContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TransferContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TransferContext" />
  <TypeSignature Language="F#" Value="type TransferContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            転送では、コンテキストを表し、その実行に関する追加のランタイム情報を提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TransferContext ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TransferContext (Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint checkpoint);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint checkpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.#ctor(Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (checkpoint As TransferCheckpoint)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferContext : Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferContext checkpoint" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="checkpoint" Type="Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint" />
      </Parameters>
      <Docs>
        <param name="checkpoint"><see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint" />の元の転送が処理が続け、最後のチェックポイントを表すオブジェクト。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TransferContext (System.IO.Stream journalStream);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream journalStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.#ctor(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (journalStream As Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.TransferContext : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.TransferContext journalStream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="journalStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="journalStream">転送ジャーナル情報が書き込まれるストリーム。 Previours を再開できる、journal のストリームからの転送を一時停止します。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public string ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As String" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : string with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクライアント要求 id を設定します。
            </summary>
        <value>クライアント要求 id を含む文字列。</value>
        <remarks>
            関連する転送操作に関連するすべての要求は、このプロパティの設定を変更、HTTP <i>x ms-クライアントの要求 id。</i>ヘッダー。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FileFailed">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; FileFailed;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; FileFailed" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.FileFailed" />
      <MemberSignature Language="VB.NET" Value="Public Event FileFailed As EventHandler(Of TransferEventArgs) " />
      <MemberSignature Language="F#" Value="member this.FileFailed : EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; " Usage="member this.FileFailed : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイル転送が失敗したときにトリガーされるイベントです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileSkipped">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; FileSkipped;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; FileSkipped" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.FileSkipped" />
      <MemberSignature Language="VB.NET" Value="Public Event FileSkipped As EventHandler(Of TransferEventArgs) " />
      <MemberSignature Language="F#" Value="member this.FileSkipped : EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; " Usage="member this.FileSkipped : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイル転送をスキップしたときにトリガーするイベントです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileTransferred">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; FileTransferred;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; FileTransferred" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.FileTransferred" />
      <MemberSignature Language="VB.NET" Value="Public Event FileTransferred As EventHandler(Of TransferEventArgs) " />
      <MemberSignature Language="F#" Value="member this.FileTransferred : EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; " Usage="member this.FileTransferred : System.EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイル転送が正常に完了したときに発生するイベント。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceOverwrite">
      <MemberSignature Language="C#" Value="public static bool ForceOverwrite (object source, object destination);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool ForceOverwrite(object source, object destination) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ForceOverwrite(System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ForceOverwrite (source As Object, destination As Object) As Boolean" />
      <MemberSignature Language="F#" Value="static member ForceOverwrite : obj * obj -&gt; bool" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ForceOverwrite (source, destination)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Object" />
        <Parameter Name="destination" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">変換先を上書きに使用するソースのインスタンス。</param>
        <param name="destination">上書きする移行先のインスタンス。</param>
        <summary>
            強制的に使用されるコールバックは、存在チェックを行わない変換先を上書きします。 変換先に資格情報のみ使用できます書き込みアクセス許可が含まれています。
            </summary>
        <returns>ファイルを上書きする場合は true。それ以外の場合は false。</returns>
        <remarks>
            コピーの状態を監視するためのサービス側のコピーで移行先の資格情報が読み取りアクセス許可が必要です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastCheckpoint">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint LastCheckpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint LastCheckpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.LastCheckpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastCheckpoint As TransferCheckpoint" />
      <MemberSignature Language="F#" Value="member this.LastCheckpoint : Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.LastCheckpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            転送の最後のチェックポイントを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogLevel">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.LogLevel LogLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.LogLevel LogLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.LogLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property LogLevel As LogLevel" />
      <MemberSignature Language="F#" Value="member this.LogLevel : Microsoft.WindowsAzure.Storage.LogLevel with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.LogLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.LogLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または関連する転送操作に使用するログ記録レベルを設定します。
            </summary>
        <value>型の値<see cref="T:Microsoft.WindowsAzure.Storage.LogLevel" />関連転送操作の記録するイベントを指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProgressHandler">
      <MemberSignature Language="C#" Value="public IProgress&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; ProgressHandler { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; ProgressHandler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ProgressHandler" />
      <MemberSignature Language="VB.NET" Value="Public Property ProgressHandler As IProgress(Of TransferStatus)" />
      <MemberSignature Language="F#" Value="member this.ProgressHandler : IProgress&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ProgressHandler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IProgress&lt;Microsoft.WindowsAzure.Storage.DataMovement.TransferStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または進行状況の更新ハンドラーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAttributesCallback">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.DataMovement.SetAttributesCallback SetAttributesCallback { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.DataMovement.SetAttributesCallback SetAttributesCallback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.SetAttributesCallback" />
      <MemberSignature Language="VB.NET" Value="Public Property SetAttributesCallback As SetAttributesCallback" />
      <MemberSignature Language="F#" Value="member this.SetAttributesCallback : Microsoft.WindowsAzure.Storage.DataMovement.SetAttributesCallback with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.SetAttributesCallback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.DataMovement.SetAttributesCallback</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または属性を設定する移行先のメモリ内で呼び出されるコールバックを設定します。 このコールバックで設定した属性は、azure ストレージ サービスに送信されます。 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldOverwriteCallback">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.DataMovement.ShouldOverwriteCallback ShouldOverwriteCallback { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.DataMovement.ShouldOverwriteCallback ShouldOverwriteCallback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ShouldOverwriteCallback" />
      <MemberSignature Language="VB.NET" Value="Public Property ShouldOverwriteCallback As ShouldOverwriteCallback" />
      <MemberSignature Language="F#" Value="member this.ShouldOverwriteCallback : Microsoft.WindowsAzure.Storage.DataMovement.ShouldOverwriteCallback with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferContext.ShouldOverwriteCallback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.DataMovement.ShouldOverwriteCallback</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または既存の変換先を上書きするかどうかに呼び出されるコールバックを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>