<Type Name="ChangeFeedHostOptions" FullName="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions">
  <TypeSignature Language="C#" Value="public class ChangeFeedHostOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ChangeFeedHostOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class ChangeFeedHostOptions" />
  <TypeSignature Language="F#" Value="type ChangeFeedHostOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.17.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            パーティションの配布で起こっているかのさまざまな側面を制御するオプション<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />インスタンス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChangeFeedHostOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckpointFrequency">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency CheckpointFrequency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency CheckpointFrequency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.CheckpointFrequency" />
      <MemberSignature Language="VB.NET" Value="Public Property CheckpointFrequency As CheckpointFrequency" />
      <MemberSignature Language="F#" Value="member this.CheckpointFrequency : Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.CheckpointFrequency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、チェックポイントのリースをどのくらいの頻度頻度。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FeedPollDelay">
      <MemberSignature Language="C#" Value="public TimeSpan FeedPollDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan FeedPollDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.FeedPollDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property FeedPollDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.FeedPollDelay : TimeSpan with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.FeedPollDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはポーリングのフィード、現在の後にすべての変更で新しい変更のパーティションをドレイン モードの間の遅延を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseAcquireInterval">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseAcquireInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseAcquireInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseAcquireInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseAcquireInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseAcquireInterval : TimeSpan with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseAcquireInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパーティションが既知のホスト インスタンス間で均等に分散かどうかを計算するタスクを開始する間隔を設定します。 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseExpirationInterval">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseExpirationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseExpirationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseExpirationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseExpirationInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseExpirationInterval : TimeSpan with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseExpirationInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパーティションを表すリースのリースが取得される間隔を設定します。 有効期限が切れると、そのリースは、この時間内で更新されていない場合と、パーティションの所有権は別に移動<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />インスタンス。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeasePrefix">
      <MemberSignature Language="C#" Value="public string LeasePrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LeasePrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeasePrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property LeasePrefix As String" />
      <MemberSignature Language="F#" Value="member this.LeasePrefix : string with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeasePrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリース id の一部として使用するプレフィックスを設定します。これは、複数をサポートするために使用できる<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />インスタンスが同じ補助コレクションを使用しているときに同じフィードを指しています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseRenewInterval">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseRenewInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseRenewInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseRenewInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseRenewInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseRenewInterval : TimeSpan with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseRenewInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定によって現在保持されているパーティションのすべてのリースの間隔の更新<see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" />インスタンス。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>