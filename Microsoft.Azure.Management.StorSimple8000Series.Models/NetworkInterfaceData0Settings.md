<Type Name="NetworkInterfaceData0Settings" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings">
  <TypeSignature Language="C#" Value="public class NetworkInterfaceData0Settings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkInterfaceData0Settings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkInterfaceData0Settings" />
  <TypeSignature Language="F#" Value="type NetworkInterfaceData0Settings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="042e1-101">' データ 0' のネットワーク インターフェイス カード設定します。</span><span class="sxs-lookup"><span data-stu-id="042e1-101">The 'Data 0' network interface card settings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceData0Settings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="042e1-102">NetworkInterfaceData0Settings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="042e1-102">Initializes a new instance of the NetworkInterfaceData0Settings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceData0Settings (string controllerZeroIp = null, string controllerOneIp = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string controllerZeroIp, string controllerOneIp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional controllerZeroIp As String = null, Optional controllerOneIp As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings : string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings (controllerZeroIp, controllerOneIp)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="controllerZeroIp" Type="System.String" />
        <Parameter Name="controllerOneIp" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="controllerZeroIp"><span data-ttu-id="042e1-103">コント ローラー 0 の IPv4 アドレスです。</span><span class="sxs-lookup"><span data-stu-id="042e1-103">The controller 0's IPv4 address.</span></span></param>
        <param name="controllerOneIp"><span data-ttu-id="042e1-104">コント ローラー 1 の IPv4 アドレスです。</span><span class="sxs-lookup"><span data-stu-id="042e1-104">The controller 1's IPv4 address.</span></span></param>
        <summary>
            <span data-ttu-id="042e1-105">NetworkInterfaceData0Settings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="042e1-105">Initializes a new instance of the NetworkInterfaceData0Settings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ControllerOneIp">
      <MemberSignature Language="C#" Value="public string ControllerOneIp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ControllerOneIp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings.ControllerOneIp" />
      <MemberSignature Language="VB.NET" Value="Public Property ControllerOneIp As String" />
      <MemberSignature Language="F#" Value="member this.ControllerOneIp : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings.ControllerOneIp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="controllerOneIp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="042e1-106">取得またはコント ローラー 1 の IPv4 アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="042e1-106">Gets or sets the controller 1's IPv4 address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ControllerZeroIp">
      <MemberSignature Language="C#" Value="public string ControllerZeroIp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ControllerZeroIp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings.ControllerZeroIp" />
      <MemberSignature Language="VB.NET" Value="Public Property ControllerZeroIp As String" />
      <MemberSignature Language="F#" Value="member this.ControllerZeroIp : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings.ControllerZeroIp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="controllerZeroIp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="042e1-107">取得またはコント ローラー 0 の IPv4 アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="042e1-107">Gets or sets the controller 0's IPv4 address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>