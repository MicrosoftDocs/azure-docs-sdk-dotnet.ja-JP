<Type Name="ControllerPowerStateChangeRequest" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest">
  <TypeSignature Language="C#" Value="public class ControllerPowerStateChangeRequest : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ControllerPowerStateChangeRequest extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ControllerPowerStateChangeRequest&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type ControllerPowerStateChangeRequest = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            コント ローラーの電源状態では、要求を変更します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ControllerPowerStateChangeRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ControllerPowerStateChangeRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ControllerPowerStateChangeRequest (Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateAction action, Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId activeController, Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus controller0State, Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus controller1State, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateAction action, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId activeController, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus controller0State, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus controller1State, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateAction,Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId,Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus,Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (action As ControllerPowerStateAction, activeController As ControllerId, controller0State As ControllerStatus, controller1State As ControllerStatus, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest : Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateAction * Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId * Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus * Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest (action, activeController, controller0State, controller1State, id, name, type, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="action" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateAction" />
        <Parameter Name="activeController" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId" />
        <Parameter Name="controller0State" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus" />
        <Parameter Name="controller1State" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
      </Parameters>
      <Docs>
        <param name="action">デバイスのコント ローラーの要求が予期している電源の状態。 使用可能な値が含まれます 'Start'、'再起動'、'シャット ダウン'。</param>
        <param name="activeController">デバイスで要求が予期しているアクティブなコント ローラー。 使用可能な値が含まれます: 'Unknown'、'None'、'Controller0'、'Controller1'</param>
        <param name="controller0State">デバイスで要求が予期しているコント ローラー 0 の状態です。 使用可能な値が含まれます: 'NotPresent'、'PoweredOff'、'Ok'、'Recovering'、'警告'、'失敗'</param>
        <param name="controller1State">デバイスで要求が予期しているコント ローラー 1 の状態です。 使用可能な値が含まれます: 'NotPresent'、'PoweredOff'、'Ok'、'Recovering'、'警告'、'失敗'</param>
        <param name="id">オブジェクトを一意に識別するパス ID です。</param>
        <param name="name">オブジェクトの名前。</param>
        <param name="type">オブジェクトの階層型です。</param>
        <param name="kind">オブジェクトの種類。 現在は Series8000 はサポートされています。 使用可能な値が含まれます: 'Series8000'</param>
        <summary>
            ControllerPowerStateChangeRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateAction Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateAction Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As ControllerPowerStateAction" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateAction with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.action")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスのコント ローラーの要求が予期している電源の状態を設定します。 使用可能な値が含まれます 'Start'、'再起動'、'シャット ダウン'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveController">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId ActiveController { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId ActiveController" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest.ActiveController" />
      <MemberSignature Language="VB.NET" Value="Public Property ActiveController As ControllerId" />
      <MemberSignature Language="F#" Value="member this.ActiveController : Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest.ActiveController" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.activeController")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスで要求が予期しているアクティブなコント ローラーを設定します。 使用可能な値が含まれます: 'Unknown'、'None'、'Controller0'、'Controller1'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Controller0State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus Controller0State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus Controller0State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest.Controller0State" />
      <MemberSignature Language="VB.NET" Value="Public Property Controller0State As ControllerStatus" />
      <MemberSignature Language="F#" Value="member this.Controller0State : Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest.Controller0State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.controller0State")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスで要求が予期しているコント ローラー 0 の状態を設定します。 使用可能な値が含まれます: 'NotPresent'、'PoweredOff'、'Ok'、'Recovering'、'警告'、'失敗'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Controller1State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus Controller1State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus Controller1State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest.Controller1State" />
      <MemberSignature Language="VB.NET" Value="Public Property Controller1State As ControllerStatus" />
      <MemberSignature Language="F#" Value="member this.Controller1State : Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest.Controller1State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.controller1State")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスで要求が予期しているコント ローラー 1 の状態を設定します。 使用可能な値が含まれます: 'NotPresent'、'PoweredOff'、'Ok'、'Recovering'、'警告'、'失敗'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="controllerPowerStateChangeRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>