<Type Name="PlatformParameters" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.PlatformParameters">
  <TypeSignature Language="C#" Value="public class PlatformParameters : Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PlatformParameters extends System.Object implements class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.PlatformParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class PlatformParameters&#xA;Implements IPlatformParameters" />
  <TypeSignature Language="F#" Value="type PlatformParameters = class&#xA;    interface IPlatformParameters" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="02d27-101">ユーザーの承認を取得中に使用される追加のパラメーター</span><span class="sxs-lookup"><span data-stu-id="02d27-101">Additional parameters used in acquiring user's authorization</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PlatformParameters (Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior promptBehavior);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior promptBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.PlatformParameters.#ctor(Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.PlatformParameters : Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.PlatformParameters" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.PlatformParameters promptBehavior" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="promptBehavior" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior" />
      </Parameters>
      <Docs>
        <param name="promptBehavior"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PlatformParameters (Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior promptBehavior, object ownerWindow);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior promptBehavior, object ownerWindow) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.PlatformParameters.#ctor(Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior,System.Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.PlatformParameters : Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior * obj -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.PlatformParameters" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.PlatformParameters (promptBehavior, ownerWindow)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="promptBehavior" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior" />
        <Parameter Name="ownerWindow" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="promptBehavior"></param>
        <param name="ownerWindow"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OwnerWindow">
      <MemberSignature Language="C#" Value="public object OwnerWindow { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object OwnerWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.PlatformParameters.OwnerWindow" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OwnerWindow As Object" />
      <MemberSignature Language="F#" Value="member this.OwnerWindow : obj" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PlatformParameters.OwnerWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02d27-102">ユーザーの資格情報を受信できるように pop ブラウザー ダイアログの所有者を取得します。</span><span class="sxs-lookup"><span data-stu-id="02d27-102">Gets the owner of the browser dialog which pops up for receiving user credentials.</span></span> <span data-ttu-id="02d27-103">これは、null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="02d27-103">It can be null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PromptBehavior">
      <MemberSignature Language="C#" Value="public Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior PromptBehavior { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior PromptBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.PlatformParameters.PromptBehavior" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PromptBehavior As PromptBehavior" />
      <MemberSignature Language="F#" Value="member this.PromptBehavior : Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PlatformParameters.PromptBehavior" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02d27-104">プロンプトの動作を取得します。</span><span class="sxs-lookup"><span data-stu-id="02d27-104">Gets prompt behavior.</span></span> <span data-ttu-id="02d27-105">場合<see cref="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Always" />ユーザーを表示する認証 ページで、別のユーザーとして認証する機会を提供するサービスを確認します。</span><span class="sxs-lookup"><span data-stu-id="02d27-105">If <see cref="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Always" />, asks service to show user the authentication page which gives them chance to authenticate as a different user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>