<Type Name="ConnectivitySettings" FullName="Microsoft.ServiceBus.ConnectivitySettings">
  <TypeSignature Language="C#" Value="public class ConnectivitySettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectivitySettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ConnectivitySettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectivitySettings" />
  <TypeSignature Language="F#" Value="type ConnectivitySettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="a323c-101">現在のアプリケーション ドメインでアクティブになっているすべての Azure サービス バス ベースのエンドポイントに対して有効な接続設定を保持します。</span><span class="sxs-lookup"><span data-stu-id="a323c-101">Holds the connectivity settings effective for all Azure Service Bus-based endpoints that are active in the current application domain.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivitySettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ConnectivitySettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="a323c-102"><see cref="T:Microsoft.ServiceBus.ConnectivitySettings" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a323c-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.ConnectivitySettings" /> class.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="connectivityMode">
      <MemberSignature Language="C#" Value="protected Microsoft.ServiceBus.ConnectivityMode connectivityMode;" />
      <MemberSignature Language="ILAsm" Value=".field family valuetype Microsoft.ServiceBus.ConnectivityMode connectivityMode" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivitySettings.connectivityMode" />
      <MemberSignature Language="VB.NET" Value="Protected connectivityMode As ConnectivityMode " />
      <MemberSignature Language="F#" Value="val mutable connectivityMode : Microsoft.ServiceBus.ConnectivityMode" Usage="Microsoft.ServiceBus.ConnectivitySettings.connectivityMode" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a323c-103">含まれています、<see cref="T:Microsoft.ServiceBus.ConnectivityMode" />現在のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="a323c-103">Contains the<see cref="T:Microsoft.ServiceBus.ConnectivityMode" /> for the current instance.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="protected virtual bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ConnectivitySettings.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="Microsoft.ServiceBus.ConnectivitySettings.IsReadOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a323c-104">接続設定は読み取り専用のかどうかを決定する値を取得します。</span><span class="sxs-lookup"><span data-stu-id="a323c-104">Gets a value that determines if the connectivity settings are read-only.</span></span> </summary>
        <value><span data-ttu-id="a323c-105">接続設定が読み取り専用の場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="a323c-105">true if the connectivity settings are read-only; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.ConnectivityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.ConnectivityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ConnectivitySettings.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As ConnectivityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.ConnectivityMode with get, set" Usage="Microsoft.ServiceBus.ConnectivitySettings.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a323c-106">取得または現在のアプリケーション ドメインの接続モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="a323c-106">Gets or sets the connectivity mode for the current application domain.</span></span> </summary>
        <value><span data-ttu-id="a323c-107">返します<see cref="T:Microsoft.ServiceBus.ConnectivityMode" />です。接続モードが含まれています。</span><span class="sxs-lookup"><span data-stu-id="a323c-107">Returns <see cref="T:Microsoft.ServiceBus.ConnectivityMode" />.Contains the connectivity mode.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>