<Type Name="MessagingException" FullName="Microsoft.ServiceBus.Messaging.MessagingException">
  <TypeSignature Language="C#" Value="public class MessagingException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MessagingException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessagingException" />
  <TypeSignature Language="VB.NET" Value="Public Class MessagingException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type MessagingException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>信号メッセージング エラーに対してスローされる例外を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessagingException : string -&gt; Microsoft.ServiceBus.Messaging.MessagingException" Usage="new Microsoft.ServiceBus.Messaging.MessagingException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <summary>指定したエラー メッセージを使用して、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingException" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MessagingException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessagingException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.ServiceBus.Messaging.MessagingException" Usage="new Microsoft.ServiceBus.Messaging.MessagingException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">シリアル化情報。</param>
        <param name="context">ストリーム コンテキスト。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingException" />クラスをシリアル化情報とストリーム コンテキストを使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessagingException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.MessagingException" Usage="new Microsoft.ServiceBus.Messaging.MessagingException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <param name="innerException">現在の例外の原因となった例外。</param>
        <summary>指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingException" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingException (string message, bool isTransientError, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, bool isTransientError, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingException.#ctor(System.String,System.Boolean,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, isTransientError As Boolean, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessagingException : string * bool * Exception -&gt; Microsoft.ServiceBus.Messaging.MessagingException" Usage="new Microsoft.ServiceBus.Messaging.MessagingException (message, isTransientError, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="isTransientError" Type="System.Boolean" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <param name="isTransientError">例外が; 一時的な場合は trueそれ以外の場合は false です。</param>
        <param name="innerException">現在の例外の原因となった例外。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.MessagingException" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public override sealed System.Collections.IDictionary Data { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.IDictionary Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingException.Data" />
      <MemberSignature Language="VB.NET" Value="Public Overrides NotOverridable ReadOnly Property Data As IDictionary" />
      <MemberSignature Language="F#" Value="member this.Data : System.Collections.IDictionary" Usage="Microsoft.ServiceBus.Messaging.MessagingException.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IDictionary</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>例外に関連付けられているデータを取得します。</summary>
        <value>例外に関連付けられているデータ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Detail">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingExceptionDetail Detail { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail Detail" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingException.Detail" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Detail As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="member this.Detail : Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingException.Detail" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージングの例外の詳細情報を設定します。</summary>
        <value>メッセージングの例外の詳細情報。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="messagingException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">スローされた例外に関するシリアル化されたオブジェクト データ。</param>
        <param name="context">転送元または変換先に関する文脈情報。</param>
        <summary>例外に関するデータをシリアル化情報を追加します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTransient">
      <MemberSignature Language="C#" Value="public bool IsTransient { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsTransient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" />
      <MemberSignature Language="VB.NET" Value="Public Property IsTransient As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsTransient : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または例外が一時的なものかどうかを示す値を設定します。 操作を再試行するかどうかを決定するには、このプロパティを確認します。</summary>
        <value>例外が; 一時的な場合は trueそれ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTime Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingException.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTime" Usage="Microsoft.ServiceBus.Messaging.MessagingException.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージングの例外が発生した時刻を設定します。</summary>
        <value>メッセージングの例外が発生した時刻。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>