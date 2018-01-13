<Type Name="MessagingExceptionDetail" FullName="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail">
  <TypeSignature Language="C#" Value="public sealed class MessagingExceptionDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessagingExceptionDetail extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessagingExceptionDetail" />
  <TypeSignature Language="F#" Value="type MessagingExceptionDetail = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>メッセージングの例外の詳細を提供します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CorrelationFiltersExceeded">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail CorrelationFiltersExceeded (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail CorrelationFiltersExceeded(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.CorrelationFiltersExceeded(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CorrelationFiltersExceeded (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member CorrelationFiltersExceeded : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.CorrelationFiltersExceeded message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外に関する説明メッセージ。</param>
        <summary>関連付けフィルターの例外の詳細を返しますでは、エラーを超えました。</summary>
        <returns>関連付けフィルターの例外の詳細は、エラーを超えています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataCommunicationError">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail DataCommunicationError (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail DataCommunicationError(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.DataCommunicationError(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DataCommunicationError (entityName As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member DataCommunicationError : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.DataCommunicationError entityName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityConflict">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityConflict (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityConflict(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityConflict(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityConflict (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityConflict : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityConflict message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外に関する説明メッセージ。</param>
        <summary>エンティティの競合エラーは例外の詳細を返します。</summary>
        <returns>エンティティの競合エラーは例外の詳細。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityConflictOperationInProgress">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityConflictOperationInProgress (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityConflictOperationInProgress(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityConflictOperationInProgress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityConflictOperationInProgress (entityName As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityConflictOperationInProgress : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityConflictOperationInProgress entityName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName">メッセージング エンティティの名前です。</param>
        <summary>進行中のエラーで、エンティティの競合は例外の詳細を返します。 競合する作成が既にある場合に発生するしたり対象のエンティティに対する保留中の呼び出しを削除できます。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityGone">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityGone (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityGone(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityGone(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityGone (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityGone : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityGone message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外に関する説明メッセージ。</param>
        <summary>エンティティになったエラーの例外の詳細を返します。</summary>
        <returns>エンティティの例外の詳細は、エラーになった。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityNotFound">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityNotFound (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityNotFound(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityNotFound(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityNotFound (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityNotFound : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityNotFound message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外に関する説明メッセージ。</param>
        <summary>エンティティが見つからないというエラーの例外の詳細を返します。</summary>
        <returns>エンティティの例外の詳細には、エラーで見つかりませんでした。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityUpdateConflict">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityUpdateConflict (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityUpdateConflict(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityUpdateConflict(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityUpdateConflict (entityName As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityUpdateConflict : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityUpdateConflict entityName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName">エンティティの名前。</param>
        <summary>エンティティの更新の競合エラーは例外の詳細を返します。</summary>
        <returns>エンティティの例外の詳細は、競合エラーを更新します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public int ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As Integer" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : int" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>エラー コードを取得します。</summary>
        <value>エラー コード。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorLevel">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevelType ErrorLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.MessagingExceptionDetail/ErrorLevelType ErrorLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorLevel As MessagingExceptionDetail.ErrorLevelType" />
      <MemberSignature Language="F#" Value="member this.ErrorLevel : Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevelType" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail+ErrorLevelType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>エラー レベルを取得します。</summary>
        <value>値のいずれか、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevelType" />列挙します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubAtFullCapacity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EventHubAtFullCapacity (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EventHubAtFullCapacity(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EventHubAtFullCapacity(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EventHubAtFullCapacity (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EventHubAtFullCapacity : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EventHubAtFullCapacity message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外に関する説明メッセージ。</param>
        <summary>返し例外の詳細と、Event Hub が最大能力で返します。 </summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>例外についてのわかりやすいメッセージを取得します。</summary>
        <value>例外に関する説明メッセージ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublisherRevoked">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail PublisherRevoked (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail PublisherRevoked(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.PublisherRevoked(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PublisherRevoked (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member PublisherRevoked : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.PublisherRevoked message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外に関する説明メッセージ。</param>
        <summary>例外に関する詳細と、Event Hubs のパブリッシャーを返しますが取り消されました。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerBusy">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail ServerBusy (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail ServerBusy(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ServerBusy(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ServerBusy (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member ServerBusy : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ServerBusy message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外に関する説明メッセージ。</param>
        <summary>Server busy エラー例外の詳細を返します。</summary>
        <returns>サーバーの例外の詳細には、エラーがビジー状態です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlFiltersExceeded">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail SqlFiltersExceeded (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail SqlFiltersExceeded(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.SqlFiltersExceeded(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlFiltersExceeded (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member SqlFiltersExceeded : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.SqlFiltersExceeded message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外に関する説明メッセージ。</param>
        <summary>SQL フィルターの例外の詳細を返しますでは、エラーを超えました。</summary>
        <returns>SQL フィルターの例外の詳細は、エラーを超えています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreLockLost">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail StoreLockLost (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail StoreLockLost(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.StoreLockLost(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function StoreLockLost (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member StoreLockLost : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.StoreLockLost message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外に関する説明メッセージ。</param>
        <summary>返します。 ストアの例外の詳細は、失われたエラーをロックします。</summary>
        <returns>ストアの例外の詳細は、失われたエラーをロックします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionsExceeded">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail SubscriptionsExceeded (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail SubscriptionsExceeded(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.SubscriptionsExceeded(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SubscriptionsExceeded (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member SubscriptionsExceeded : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.SubscriptionsExceeded message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外に関する説明メッセージ。</param>
        <summary>サブスクリプションの場合、例外の詳細を返しますでは、エラーを超えました。</summary>
        <returns>サブスクリプションの場合、例外の詳細は、エラーを超えています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnknownDetail">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail UnknownDetail (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail UnknownDetail(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.UnknownDetail(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UnknownDetail (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member UnknownDetail : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.UnknownDetail message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外に関する説明メッセージ。</param>
        <summary>不明な詳細エラーの例外の詳細を返します。</summary>
        <returns>不明な詳細エラーの例外の詳細。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnspecifiedInternalError">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail UnspecifiedInternalError (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail UnspecifiedInternalError(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.UnspecifiedInternalError(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UnspecifiedInternalError (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member UnspecifiedInternalError : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.UnspecifiedInternalError message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外に関する説明メッセージ。</param>
        <summary>未指定の内部エラーの例外の詳細を返します。</summary>
        <returns>未指定の内部エラーの例外の詳細。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>