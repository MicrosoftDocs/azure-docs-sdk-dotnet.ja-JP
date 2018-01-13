<Type Name="ActorServiceRemotingDispatcher" FullName="Microsoft.ServiceFabric.Actors.Remoting.V1.Runtime.ActorServiceRemotingDispatcher">
  <TypeSignature Language="C#" Value="public class ActorServiceRemotingDispatcher : Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActorServiceRemotingDispatcher extends Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.V1.Runtime.ActorServiceRemotingDispatcher" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorServiceRemotingDispatcher&#xA;Inherits ServiceRemotingDispatcher" />
  <TypeSignature Language="F#" Value="type ActorServiceRemotingDispatcher = class&#xA;    inherit ServiceRemotingDispatcher" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.ServiceRemotingDispatcher</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            実装を提供<see cref="T:Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingMessageHandler" />アクター サービスとサービスでホストされているアクターのメッセージをディスパッチすることができます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorServiceRemotingDispatcher (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V1.Runtime.ActorServiceRemotingDispatcher.#ctor(Microsoft.ServiceFabric.Actors.Runtime.ActorService)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Remoting.V1.Runtime.ActorServiceRemotingDispatcher : Microsoft.ServiceFabric.Actors.Runtime.ActorService -&gt; Microsoft.ServiceFabric.Actors.Remoting.V1.Runtime.ActorServiceRemotingDispatcher" Usage="new Microsoft.ServiceFabric.Actors.Remoting.V1.Runtime.ActorServiceRemotingDispatcher actorService" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
      </Parameters>
      <Docs>
        <param name="actorService">アクター サービス インスタンス。</param>
        <summary>
            アクター サービスとサービスでホストされているアクターのメッセージをディスパッチできます ActorServiceRemotingDispatcher をインスタンス化には.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestResponseAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;byte[]&gt; RequestResponseAsync (Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext requestContext, Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, byte[] requestBodyBytes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; RequestResponseAsync(class Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext requestContext, class Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders messageHeaders, unsigned int8[] requestBodyBytes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.V1.Runtime.ActorServiceRemotingDispatcher.RequestResponseAsync(Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext,Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function RequestResponseAsync (requestContext As IServiceRemotingRequestContext, messageHeaders As ServiceRemotingMessageHeaders, requestBodyBytes As Byte()) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="override this.RequestResponseAsync : Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext * Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders * byte[] -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="actorServiceRemotingDispatcher.RequestResponseAsync (requestContext, messageHeaders, requestBodyBytes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestContext" Type="Microsoft.ServiceFabric.Services.Remoting.V1.Runtime.IServiceRemotingRequestContext" />
        <Parameter Name="messageHeaders" Type="Microsoft.ServiceFabric.Services.Remoting.V1.ServiceRemotingMessageHeaders" />
        <Parameter Name="requestBodyBytes" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="requestContext">必要な場合は、コールバック チャネルを取得できるようにするコンテキストを要求します。</param>
        <param name="messageHeaders">サービスのリモート処理のメッセージ ヘッダー</param>
        <param name="requestBodyBytes">リモート処理のメッセージの要求本文をシリアル化されます。</param>
        <summary>
            アクター サービス メソッドまたはアクター メソッドに、クライアントから受信したメッセージをディスパッチします。
            </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。 タスクの結果は、シリアル化された応答の本体です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>