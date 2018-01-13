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
    <summary><span data-ttu-id="07c7d-101">Azure アクセス制御で使用可能な一方向の接続の種類を表します。</span><span class="sxs-lookup"><span data-stu-id="07c7d-101">Represents the different types of one-way connections available through the Azure Access Control.</span></span></summary>
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
        <summary><span data-ttu-id="07c7d-102">複数のサービス アプリケーションが、指定したエンドポイントで受信待ちすることを指定します。</span><span class="sxs-lookup"><span data-stu-id="07c7d-102">Specifies that multiple service applications may listen on a given endpoint.</span></span> <span data-ttu-id="07c7d-103"><see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" /> で使用されます。</span><span class="sxs-lookup"><span data-stu-id="07c7d-103">Used by <see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" />.</span></span> </summary>
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
        <summary><span data-ttu-id="07c7d-104">1 つのサービス アプリケーションが、指定したエンドポイントをリッスンできることを指定します。</span><span class="sxs-lookup"><span data-stu-id="07c7d-104">Specifies that only one service application can listen on a given endpoint.</span></span> <span data-ttu-id="07c7d-105"><see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" /> で使用されます。</span><span class="sxs-lookup"><span data-stu-id="07c7d-105">Used by <see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" />.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>