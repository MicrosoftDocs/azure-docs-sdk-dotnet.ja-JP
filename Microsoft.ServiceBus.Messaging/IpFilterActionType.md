<Type Name="IpFilterActionType" FullName="Microsoft.ServiceBus.Messaging.IpFilterActionType">
  <TypeSignature Language="C#" Value="public enum IpFilterActionType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed IpFilterActionType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.IpFilterActionType" />
  <TypeSignature Language="VB.NET" Value="Public Enum IpFilterActionType" />
  <TypeSignature Language="F#" Value="type IpFilterActionType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="IpFilterActionType", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5d9f5-101">IpFilter に一致する ip アドレスが適用される動作の種類を表します。</span><span class="sxs-lookup"><span data-stu-id="5d9f5-101">Represent the type of action the ip that match the IpFilter is applied to.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Accept">
      <MemberSignature Language="C#" Value="Accept" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.IpFilterActionType Accept = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.IpFilterActionType.Accept" />
      <MemberSignature Language="VB.NET" Value="Accept" />
      <MemberSignature Language="F#" Value="Accept = 1" Usage="Microsoft.ServiceBus.Messaging.IpFilterActionType.Accept" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.IpFilterActionType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d9f5-102">Ip が一致している場合、接続が許可されます。</span><span class="sxs-lookup"><span data-stu-id="5d9f5-102">If an Ip is matched, the connection is allowed.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Reject">
      <MemberSignature Language="C#" Value="Reject" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.IpFilterActionType Reject = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.IpFilterActionType.Reject" />
      <MemberSignature Language="VB.NET" Value="Reject" />
      <MemberSignature Language="F#" Value="Reject = 0" Usage="Microsoft.ServiceBus.Messaging.IpFilterActionType.Reject" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.IpFilterActionType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d9f5-103">Ip が一致すると、サービスへの接続から Ip は拒否されます。</span><span class="sxs-lookup"><span data-stu-id="5d9f5-103">If an Ip is matched, the Ip is rejected from connecting to the service.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>