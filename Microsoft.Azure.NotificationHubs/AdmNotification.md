<Type Name="AdmNotification" FullName="Microsoft.Azure.NotificationHubs.AdmNotification">
  <TypeSignature Language="C#" Value="public sealed class AdmNotification : Microsoft.Azure.NotificationHubs.Notification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AdmNotification extends Microsoft.Azure.NotificationHubs.Notification" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.AdmNotification" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AdmNotification&#xA;Inherits Notification" />
  <TypeSignature Language="F#" Value="type AdmNotification = class&#xA;    inherit Notification" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Notification</BaseTypeName>
  </Base>
  <Interfaces></Interfaces>
  <Docs>
    <summary><span data-ttu-id="f0065-101">Amazon デバイス メッセージング (ADM) 通知を表します。</span><span class="sxs-lookup"><span data-stu-id="f0065-101">Represents the Amazon Device Messaging (ADM) notification.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdmNotification (string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AdmNotification.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jsonPayload As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AdmNotification : string -&gt; Microsoft.Azure.NotificationHubs.AdmNotification" Usage="new Microsoft.Azure.NotificationHubs.AdmNotification jsonPayload" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="f0065-102">JSON ペイロード。</span><span class="sxs-lookup"><span data-stu-id="f0065-102">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="f0065-103"><see cref="T:Microsoft.Azure.NotificationHubs.AdmNotification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f0065-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.AdmNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidateAndPopulateHeaders">
      <MemberSignature Language="C#" Value="protected override void OnValidateAndPopulateHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidateAndPopulateHeaders() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AdmNotification.OnValidateAndPopulateHeaders" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidateAndPopulateHeaders ()" />
      <MemberSignature Language="F#" Value="override this.OnValidateAndPopulateHeaders : unit -&gt; unit" Usage="admNotification.OnValidateAndPopulateHeaders " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f0065-104">検証し、ヘッダーを追加します。</span><span class="sxs-lookup"><span data-stu-id="f0065-104">Validate and populates the headers.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformType">
      <MemberSignature Language="C#" Value="protected override string PlatformType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlatformType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AdmNotification.PlatformType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property PlatformType As String" />
      <MemberSignature Language="F#" Value="member this.PlatformType : string" Usage="Microsoft.Azure.NotificationHubs.AdmNotification.PlatformType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0065-105">プラットフォームの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0065-105">Gets the type of the platform.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f0065-106">プラットフォームの種類。</span><span class="sxs-lookup"><span data-stu-id="f0065-106">The type of the platform.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>