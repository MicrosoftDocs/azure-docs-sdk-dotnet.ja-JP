<Type Name="MobileAppSettingsProvider" FullName="Microsoft.Azure.Mobile.Server.Config.MobileAppSettingsProvider">
  <TypeSignature Language="C#" Value="public class MobileAppSettingsProvider : Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileAppSettingsProvider extends System.Object implements class Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Config.MobileAppSettingsProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileAppSettingsProvider&#xA;Implements IMobileAppSettingsProvider" />
  <TypeSignature Language="F#" Value="type MobileAppSettingsProvider = class&#xA;    interface IMobileAppSettingsProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            既定の実装を提供<see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider" />グローバルからサービスの設定を取得する<see cref="T:System.Configuration.ConfigurationManager" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileAppSettingsProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppSettingsProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppSettingsProvider" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAppSettings">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Specialized.NameValueCollection GetAppSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Specialized.NameValueCollection GetAppSettings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppSettingsProvider.GetAppSettings" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function GetAppSettings () As NameValueCollection" />
      <MemberSignature Language="F#" Value="abstract member GetAppSettings : unit -&gt; System.Collections.Specialized.NameValueCollection&#xA;override this.GetAppSettings : unit -&gt; System.Collections.Specialized.NameValueCollection" Usage="mobileAppSettingsProvider.GetAppSettings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Specialized.NameValueCollection</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Mockable 方法では、現在のアプリケーション設定を取得します。
            </summary>
        <returns>A<see cref="T:System.Collections.Specialized.NameValueCollection" />アプリケーション設定を格納します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMobileAppSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary GetMobileAppSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary GetMobileAppSettings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppSettingsProvider.GetMobileAppSettings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMobileAppSettings () As MobileAppSettingsDictionary" />
      <MemberSignature Language="F#" Value="abstract member GetMobileAppSettings : unit -&gt; Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary&#xA;override this.GetMobileAppSettings : unit -&gt; Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" Usage="mobileAppSettingsProvider.GetMobileAppSettings " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider.GetMobileAppSettings</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="InitializeSettings">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary InitializeSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary InitializeSettings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppSettingsProvider.InitializeSettings" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function InitializeSettings () As MobileAppSettingsDictionary" />
      <MemberSignature Language="F#" Value="abstract member InitializeSettings : unit -&gt; Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary&#xA;override this.InitializeSettings : unit -&gt; Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" Usage="mobileAppSettingsProvider.InitializeSettings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            初期化、<see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" />への応答で提供される<see cref="M:GetMobileAppSettings" />です。
            </summary>
        <returns>完全に初期化された<see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>