<Type Name="ITransportSettings" FullName="Microsoft.Azure.Devices.Client.ITransportSettings">
  <TypeSignature Language="C#" Value="public interface ITransportSettings" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITransportSettings" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.ITransportSettings" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITransportSettings" />
  <TypeSignature Language="F#" Value="type ITransportSettings = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3d74d-101">DeviceClient のさまざまなトランスポートに固有の設定を定義するためのインターフェイス</span><span class="sxs-lookup"><span data-stu-id="3d74d-101">Interface used to define various transport-specific settings for DeviceClient</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefaultReceiveTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan DefaultReceiveTimeout { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DefaultReceiveTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.ITransportSettings.DefaultReceiveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultReceiveTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DefaultReceiveTimeout : TimeSpan" Usage="Microsoft.Azure.Devices.Client.ITransportSettings.DefaultReceiveTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTransportType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Client.TransportType GetTransportType ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance valuetype Microsoft.Azure.Devices.Client.TransportType GetTransportType() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.ITransportSettings.GetTransportType" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTransportType () As TransportType" />
      <MemberSignature Language="F#" Value="abstract member GetTransportType : unit -&gt; Microsoft.Azure.Devices.Client.TransportType" Usage="iTransportSettings.GetTransportType " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.TransportType</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>