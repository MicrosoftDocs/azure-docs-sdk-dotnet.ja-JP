<Type Name="RelayedOnewayConnectionMode" FullName="Microsoft.ServiceBus.RelayedOnewayConnectionMode">
  <TypeSignature Language="C#" Value="public enum RelayedOnewayConnectionMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RelayedOnewayConnectionMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.RelayedOnewayConnectionMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum RelayedOnewayConnectionMode" />
  <TypeSignature Language="F#" Value="type RelayedOnewayConnectionMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>Azure アクセス制御で使用可能な一方向の接続の種類を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Multicast">
      <MemberSignature Language="C#" Value="Multicast" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.RelayedOnewayConnectionMode Multicast = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.RelayedOnewayConnectionMode.Multicast" />
      <MemberSignature Language="VB.NET" Value="Multicast" />
      <MemberSignature Language="F#" Value="Multicast = 1" Usage="Microsoft.ServiceBus.RelayedOnewayConnectionMode.Multicast" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayedOnewayConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>複数のサービス アプリケーションが、指定したエンドポイントで受信待ちすることを指定します。 <see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" /> で使用されます。 </summary>
      </Docs>
    </Member>
    <Member MemberName="Unicast">
      <MemberSignature Language="C#" Value="Unicast" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.RelayedOnewayConnectionMode Unicast = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.RelayedOnewayConnectionMode.Unicast" />
      <MemberSignature Language="VB.NET" Value="Unicast" />
      <MemberSignature Language="F#" Value="Unicast = 0" Usage="Microsoft.ServiceBus.RelayedOnewayConnectionMode.Unicast" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayedOnewayConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>1 つのサービス アプリケーションが、指定したエンドポイントをリッスンできることを指定します。 <see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" /> で使用されます。</summary>
      </Docs>
    </Member>
  </Members>
</Type>