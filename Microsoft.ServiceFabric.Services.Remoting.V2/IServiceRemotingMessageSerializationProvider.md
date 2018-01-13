<Type Name="IServiceRemotingMessageSerializationProvider" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingMessageSerializationProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingMessageSerializationProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingMessageSerializationProvider" />
  <TypeSignature Language="F#" Value="type IServiceRemotingMessageSerializationProvider = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            リモート処理の要求に対してカスタムのシリアル化を提供するために実装する必要がありますのあるインターフェイスを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateMessageBodyFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory CreateMessageBodyFactory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory CreateMessageBodyFactory() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider.CreateMessageBodyFactory" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageBodyFactory () As IServiceRemotingMessageBodyFactory" />
      <MemberSignature Language="F#" Value="abstract member CreateMessageBodyFactory : unit -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory" Usage="iServiceRemotingMessageSerializationProvider.CreateMessageBodyFactory " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            リモート処理の要求と応答の本文を作成するために使用される IServiceRemotingMessageBodyFactory を作成します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRequestMessageSerializer">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer CreateRequestMessageSerializer (Type serviceInterfaceType, System.Collections.Generic.IEnumerable&lt;Type&gt; requestBodyTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer CreateRequestMessageSerializer(class System.Type serviceInterfaceType, class System.Collections.Generic.IEnumerable`1&lt;class System.Type&gt; requestBodyTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider.CreateRequestMessageSerializer(System.Type,System.Collections.Generic.IEnumerable{System.Type})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRequestMessageSerializer (serviceInterfaceType As Type, requestBodyTypes As IEnumerable(Of Type)) As IServiceRemotingRequestMessageBodySerializer" />
      <MemberSignature Language="F#" Value="abstract member CreateRequestMessageSerializer : Type * seq&lt;Type&gt; -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer" Usage="iServiceRemotingMessageSerializationProvider.CreateRequestMessageSerializer (serviceInterfaceType, requestBodyTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBodySerializer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceInterfaceType" Type="System.Type" />
        <Parameter Name="requestBodyTypes" Type="System.Collections.Generic.IEnumerable&lt;System.Type&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceInterfaceType">サービスのユーザー インターフェイス</param>
        <param name="requestBodyTypes">ServiceInterfaceType 内のすべてのメソッドのパラメーター</param>
        <summary>
            Serviceinterface IServiceRemotingRequestMessageBodySerializer を作成します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateResponseMessageSerializer">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer CreateResponseMessageSerializer (Type serviceInterfaceType, System.Collections.Generic.IEnumerable&lt;Type&gt; responseBodyTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer CreateResponseMessageSerializer(class System.Type serviceInterfaceType, class System.Collections.Generic.IEnumerable`1&lt;class System.Type&gt; responseBodyTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageSerializationProvider.CreateResponseMessageSerializer(System.Type,System.Collections.Generic.IEnumerable{System.Type})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateResponseMessageSerializer (serviceInterfaceType As Type, responseBodyTypes As IEnumerable(Of Type)) As IServiceRemotingResponseMessageBodySerializer" />
      <MemberSignature Language="F#" Value="abstract member CreateResponseMessageSerializer : Type * seq&lt;Type&gt; -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer" Usage="iServiceRemotingMessageSerializationProvider.CreateResponseMessageSerializer (serviceInterfaceType, responseBodyTypes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBodySerializer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceInterfaceType" Type="System.Type" />
        <Parameter Name="responseBodyTypes" Type="System.Collections.Generic.IEnumerable&lt;System.Type&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceInterfaceType">サービスのユーザー インターフェイス</param>
        <param name="responseBodyTypes">ServiceInterfaceType 内のすべてのメソッドの戻り値の型</param>
        <summary>
             Serviceinterface IServiceRemotingResponseMessageBodySerializer を作成します。
             </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>