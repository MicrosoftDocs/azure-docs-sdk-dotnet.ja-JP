<Type Name="ConnectivityParameters" FullName="Microsoft.Azure.Management.Network.Models.ConnectivityParameters">
  <TypeSignature Language="C#" Value="public class ConnectivityParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectivityParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ConnectivityParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectivityParameters" />
  <TypeSignature Language="F#" Value="type ConnectivityParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="85fbd-101">接続の確認を実行する方法を決定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="85fbd-101">Parameters that determine how the connectivity check will be performed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="85fbd-102">ConnectivityParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="85fbd-102">Initializes a new instance of the ConnectivityParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityParameters (Microsoft.Azure.Management.Network.Models.ConnectivitySource source, Microsoft.Azure.Management.Network.Models.ConnectivityDestination destination);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Network.Models.ConnectivitySource source, class Microsoft.Azure.Management.Network.Models.ConnectivityDestination destination) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityParameters.#ctor(Microsoft.Azure.Management.Network.Models.ConnectivitySource,Microsoft.Azure.Management.Network.Models.ConnectivityDestination)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (source As ConnectivitySource, destination As ConnectivityDestination)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ConnectivityParameters : Microsoft.Azure.Management.Network.Models.ConnectivitySource * Microsoft.Azure.Management.Network.Models.ConnectivityDestination -&gt; Microsoft.Azure.Management.Network.Models.ConnectivityParameters" Usage="new Microsoft.Azure.Management.Network.Models.ConnectivityParameters (source, destination)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Management.Network.Models.ConnectivitySource" />
        <Parameter Name="destination" Type="Microsoft.Azure.Management.Network.Models.ConnectivityDestination" />
      </Parameters>
      <Docs>
        <param name="source">To be added.</param>
        <param name="destination">To be added.</param>
        <summary>
            <span data-ttu-id="85fbd-103">ConnectivityParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="85fbd-103">Initializes a new instance of the ConnectivityParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Destination">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.ConnectivityDestination Destination { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.ConnectivityDestination Destination" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityParameters.Destination" />
      <MemberSignature Language="VB.NET" Value="Public Property Destination As ConnectivityDestination" />
      <MemberSignature Language="F#" Value="member this.Destination : Microsoft.Azure.Management.Network.Models.ConnectivityDestination with get, set" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityParameters.Destination" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destination")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectivityDestination</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.ConnectivitySource Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.ConnectivitySource Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityParameters.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As ConnectivitySource" />
      <MemberSignature Language="F#" Value="member this.Source : Microsoft.Azure.Management.Network.Models.ConnectivitySource with get, set" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityParameters.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectivitySource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="connectivityParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="85fbd-104">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="85fbd-104">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="85fbd-105">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="85fbd-105">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>